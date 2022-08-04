---
title: IExternalResourceResolver
second_title: Aspose.Sildes for Java API Reference
description: p
 Callback interface used to resolve external resources during Html Svg documents import.
type: docs
weight: 763
url: /java/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback interface used to resolve external resources during Html, Svg documents import.
## Methods

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
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
public abstract InputStream getEntity(String absoluteUri)
```


Maps a URI to an object containing the actual resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Returns:**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.
