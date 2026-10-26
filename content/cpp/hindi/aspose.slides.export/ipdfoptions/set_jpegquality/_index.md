---
title: set_JpegQuality()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें uint8_t.
type: docs
weight: 196
url: /hi/aspose.slides.export/ipdfoptions/set_jpegquality/
---
## IPdfOptions::set_JpegQuality(uint8_t) विधि


PDF दस्तावेज़ के भीतर JPEG चित्रों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें **uint8_t**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_JpegQuality(uint8_t value)=0
```

## टिप्पणियाँ


केवल तब प्रभाव होता है जब किसी दस्तावेज़ में JPEG चित्र होते हैं।

जब PDF प्रारूप में सहेजते समय दस्तावेज़ के भीतर चित्रों की गुणवत्ता प्राप्त या सेट करने के लिए इस गुण का उपयोग करें। मान 0 से 100 के बीच हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सर्वोत्तम गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **100** है।
## संबंधित देखें

* क्लास [IPdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)