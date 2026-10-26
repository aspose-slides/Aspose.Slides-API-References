---
title: set_JpegQuality()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: PDF दस्तावेज़ के भीतर JPEG चित्रों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें uint8_t.
type: docs
weight: 92
url: /hi/aspose.slides.export/ihtmloptions/set_jpegquality/
---
## IHtmlOptions::set_JpegQuality(uint8_t) विधि

PDF दस्तावेज़ के भीतर JPEG चित्रों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें **uint8_t**।

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_JpegQuality(uint8_t value)=0
```

## टिप्पणियाँ

केवल तब प्रभावी होता है जब दस्तावेज़ में JPEG चित्र होते हैं।

इस गुण का उपयोग करते हुए दस्तावेज़ को PDF प्रारूप में सहेजते समय चित्रों की गुणवत्ता प्राप्त या सेट करें। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न है और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है।

डिफ़ॉल्ट मान **95** है।
## देखें

* क्लास [IHtmlOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)