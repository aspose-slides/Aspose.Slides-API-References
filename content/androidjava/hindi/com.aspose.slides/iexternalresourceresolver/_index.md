---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Html, Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए प्रयुक्त कॉलबैक इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Html, Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए प्रयुक्त कॉलबैक इंटरफ़ेस।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | आधार और सापेक्ष URI से पूर्ण URI प्राप्त करता है। |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | एक URI को वास्तविक संसाधन रखने वाले ऑब्जेक्ट से मैप करता है। |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

आधार और सापेक्ष URI से पूर्ण URI प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | java.lang.String | लिंकिंग ऑब्जेक्ट्स का आधार URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का सापेक्ष URI। |

**रिटर्न मान:**
java.lang.String - पूर्ण URI या यदि सापेक्ष URI हल नहीं किया जा सके तो null।

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

एक URI को वास्तविक संसाधन रखने वाले ऑब्जेक्ट से मैप करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का पूर्ण URI। |

**रिटर्न मान:**
java.io.InputStream - एक InputStream ऑब्जेक्ट या यदि संसाधन को स्ट्रीम नहीं किया जा सकता तो null।