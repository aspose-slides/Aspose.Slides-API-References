---
title: HtmlExternalResolver
second_title: Aspose.Slides for Java API संदर्भ
description: HTML इम्पोर्ट रूटीन द्वारा उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट, जो छवियों जैसे संदर्भित ऑब्जेक्ट्स प्राप्त करता है।
type: docs
url: /hi/com.aspose.slides/htmlexternalresolver/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML इम्पोर्ट रूटीन द्वारा उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट, जैसे छवियों जैसे संदर्भित ऑब्जेक्ट प्राप्त करने के लिए।

--------------------

इस रेज़ॉल्वर का उपयोग करने से एक सुरक्षा कमजोरी उत्पन्न हो सकती है जब क्लाइंट द्वारा प्रदान की गई HTML फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने का कारण बनती है। सावधानी से उपयोग करें। यह अनुशंसित है कि HtmlExternalResolver को बिल्कुल न निर्दिष्ट करें (केवल एम्बेडेड ऑब्जेक्ट पढ़े जाएँगे) या ऐसा कोई सबक्लास बनाएँ जो जाँच करे कि निर्दिष्ट URI मान्य है या नहीं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

बेस और रिलेटिव URI से एब्सोल्यूट URI को रिजॉल्व करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | java.lang.String | लिंकिंग ऑब्जेक्ट्स का बेस URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का रिलेटिव URI। |

**रिटर्न:**
java.lang.String - एब्सोल्यूट URI या null यदि रिलेटिव URI को रिजॉल्व नहीं किया जा सकता।

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

एक URI को वास्तविक संसाधन रखता ऑब्जेक्ट से मैप करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का एब्सोल्यूट URI। |

**रिटर्न:**
java.io.InputStream - एक InputStream ऑब्जेक्ट या null यदि संसाधन को स्ट्रीम नहीं किया जा सकता।