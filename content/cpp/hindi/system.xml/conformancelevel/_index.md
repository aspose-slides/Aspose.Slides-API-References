---
title: ConformanceLevel
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह निर्धारित करता है कि XmlReader और XmlWriter वस्तुएँ इनपुट या आउटपुट जाँच की कितनी मात्रा करती हैं।
type: docs
weight: 625
url: /hi/system.xml/conformancelevel/
---
## ConformanceLevel enum

Specifies the amount of input or output checking that [XmlReader](../xmlreader/) and [XmlWriter](../xmlwriter/) objects perform.

```cpp
enum class ConformanceLevel
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | 0 | The [XmlReader](../xmlreader/) या [XmlWriter](../xmlwriter/) वस्तु स्वत: पता लगाती है कि दस्तावेज़-स्तर या अंश-स्तर की जाँच की जानी चाहिए या नहीं, और उपयुक्त जाँच करती है। यदि आप किसी अन्य [XmlReader](../xmlreader/) या [XmlWriter](../xmlwriter/) वस्तु को लपेट रहे हैं, तो बाहरी वस्तु अतिरिक्त अनुरूपता जाँच नहीं करती। अनुरूपता जाँच को अंतर्निहित वस्तु पर छोड़ दिया जाता है। |
| Fragment | 1 | XML डेटा [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) है, जैसा कि W3C द्वारा परिभाषित किया गया है। यह अनुरूपता स्तर एक XML दस्तावेज़ का प्रतिनिधित्व करता है जिसमें मूल तत्व नहीं हो सकता है लेकिन अन्यथा सही ढंग से बनाया गया है। इस जाँच स्तर से यह सुनिश्चित होता है कि पढ़ी या लिखी जा रही धारा को किसी भी प्रोसेसर द्वारा [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) के रूप में उपभोग किया जा सके। |
| Document | 2 | XML डेटा [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) के लिए निर्धारित नियमों के अनुरूप है, जैसा कि W3C द्वारा परिभाषित किया गया है। यह जाँच स्तर यह सुनिश्चित करता है कि पढ़ी या लिखी जा रही धारा को किसी भी प्रोसेसर द्वारा [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) के रूप में उपभोग किया जा सके। |

## संबंधित देखें

* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)