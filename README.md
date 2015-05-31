# taybiz-xml-core
A collection of XML resources for working with SOAP and RESTful services.

An example error/fault payload that I expect to validate.
The uriRef is very linked-data/symantic web friendly. It's built to be compatible with Owl and RDF. Use at your discretion.
```
<Error xmlns="http://api.taybiz.com/xml/core/1.0">
        <Code>NoSuchKey</Code>
        <Message>The resource you requested does not exist</Message>
        <Key>
                <Id uriRef="http://www.whatever.com/MAXIMOv6/PR#ORGID">TAYBIZ</Id>
                <Id uriRef="http://www.whatever.com/MAXIMOv6/PR#SITEID">COLORADO</Id>
                <Id uriRef="http://www.whatever.com/MAXIMOv6/PR#PRNUM">123</Id>
        </Key>
        <RequestId>123</RequestId>
</Error>
```
