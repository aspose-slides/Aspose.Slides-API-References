---
title: ExternalResourceResolver
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: HTML और SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग की जाने वाली कॉलबैक क्लास।
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

HTML, SVG दस्तावेज़ आयात के दौरान बाहरी संसाधनों को हल करने के लिए उपयोग की जाने वाली कॉलबैक क्लास।

--------------------

इस रिज़ॉल्वर का उपयोग करने से सुरक्षा जोखिम पैदा हो सकता है जब क्लाइंट द्वारा प्रदान की गई HTML या SVG फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने के लिए मजबूर करती है। सावधानी से उपयोग करें। यह सिफ़ारिश की जाती है कि ExternalResourceResolver को बिल्कुल भी निर्दिष्ट न किया जाए (केवल एम्बेडेड ऑब्जेक्ट पढ़े जाएंगे) या कोई ऐसा उपवर्ग बनाया जाए जो जाँच करे कि निर्दिष्ट uri मान्य है या नहीं।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | बेस और रिलेटिव URI से पूर्ण URI को हल करता है। |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | एक URI को वास्तविक संसाधन वाले ऑब्जेक्ट से मैप करता है। |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

बेस और रिलेटिव URI से पूर्ण URI को हल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | java.lang.String | लिंकिंग ऑब्जेक्ट्स का बेस URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का रिलेटिव URI |

**रिटर्न:**
java.lang.String - पूर्ण URI या null यदि रिलेटिव URI को हल नहीं किया जा सकता।

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

एक URI को वास्तविक संसाधन वाले ऑब्जेक्ट से मैप करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का पूर्ण URI |

**रिटर्न:**
java.io.InputStream - एक InputStream ऑब्जेक्ट या null यदि संसाधन को स्ट्रीम नहीं किया जा सकता।