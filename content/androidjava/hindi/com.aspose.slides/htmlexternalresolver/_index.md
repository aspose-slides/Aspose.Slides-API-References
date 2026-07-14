---
title: HtmlExternalResolver
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: HTML आयात रूटीन द्वारा छवियों जैसी संदर्भित वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट।
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

HTML आयात प्रक्रिया द्वारा छवियों जैसी संदर्भित वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट।

--------------------

इस रिज़ॉल्वर का उपयोग करने से एक सुरक्षा कमजोरी उत्पन्न हो सकती है जब क्लाइंट द्वारा प्रदान किया गया HTML फ़ाइल सर्वर सॉफ़्टवेयर को स्थानीय या नेटवर्क फ़ाइल प्राप्त करने का कारण बनती है। सावधानी से उपयोग करें। यह अनुशंसा की जाती है कि HtmlExternalResolver को पूरी तरह से निर्दिष्ट न किया जाए (केवल एम्बेडेड ऑब्जेक्ट पढ़े जाएंगे) या कोई सबक्लास बनाया जाए जो जाँचता हो कि निर्दिष्ट URI वैध है या नहीं।

## निर्माता

| निर्माता | विवरण |
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

बेस और रिलेटिव URI से पूर्ण URI को हल करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | java.lang.String | लिंक करने वाले ऑब्जेक्ट का बेस URI |
| relativeUri | java.lang.String | लिंक्ड ऑब्जेक्ट का रिलेटिव URI. |

**रिटर्न:**
java.lang.String - पूर्ण URI या null यदि रिलेटिव URI हल नहीं हो सके।

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

एक URI को वास्तविक संसाधन रखने वाले ऑब्जेक्ट से मैप करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | java.lang.String | ऑब्जेक्ट का पूर्ण URI. |

**रिटर्न:**
java.io.InputStream - एक InputStream ऑब्जेक्ट या null यदि संसाधन को स्ट्रीम नहीं किया जा सकता।