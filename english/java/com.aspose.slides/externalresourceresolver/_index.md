---
title: ExternalResourceResolver
second_title: Aspose.Sildes for Java API Reference
description: p
 Callback class used to resolve external resources during Html Svg documents import.
type: docs
weight: 184
url: /java/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Callback class used to resolve external resources during Html, Svg documents import.

--------------------

Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Methods

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resolves the absolute URI from the base and relative URIs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Returns:**
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Maps a URI to an object containing the actual resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Returns:**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.
