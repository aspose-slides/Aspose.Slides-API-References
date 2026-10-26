---
title: ExternalResourceResolver
second_title: Aspose.Slides for Java API संदर्भ
description: Html और Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक क्लास।
type: docs
url: /hi/com.aspose.slides/externalresourceresolver/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Html और Svg दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला कॉलबैक क्लास।

--------------------

इस रेज़ॉल्वर का उपयोग करने से एक भेद्यता उत्पन्न हो सकती है जब क्लाइंट द्वारा प्रदान किया गया HTML या SVG फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने के लिए प्रेरित करती है। सावधानी से उपयोग करें। यह अनुशंसा की जाती है कि ExternalResourceResolver को बिल्कुल न निर्दिष्ट किया जाए (केवल एम्बेडेड ऑब्जेक्ट पढ़े जाएंगे) या कोई उपवर्ग बनाया जाए जो यह जांचे कि निर्दिष्ट uri वैध है या नहीं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | मूल और सापेक्ष URI से पूर्ण URI को हल करता है। |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | एक URI को वास्तविक संसाधन वाली वस्तु से मैप करता है। |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


मूल और सापेक्ष URI से पूर्ण URI को हल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | java.lang.String | लिंकिंग ऑब्जेक्ट्स का बेस URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का सापेक्ष URI। |

**वापसी:**
java.lang.String - पूर्ण URI या null यदि सापेक्ष URI को हल नहीं किया जा सकता।
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


एक URI को वास्तविक संसाधन वाली वस्तु से मैप करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का पूर्ण URI। |

**वापसी:**
java.io.InputStream - एक InputStream वस्तु या null यदि संसाधन को स्ट्रीम नहीं किया जा सकता।