---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Html और Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Html, Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

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
| baseUri | java.lang.String | लिंकिंग ऑब्जेक्ट्स का बेस URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का रिलेटिव URI |

**Returns:**
java.lang.String - एब्सॉल्यूट URI या null यदि रिलेटिव URI को हल नहीं किया जा सकता।

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Maps a URI to an object containing the actual resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का एब्सॉल्यूट URI |

**Returns:**
java.io.InputStream - एक InputStream ऑब्जेक्ट या null यदि संसाधन को स्ट्रीम नहीं किया जा सकता।