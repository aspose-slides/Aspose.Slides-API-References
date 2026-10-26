---
title: get_Character()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "उच्चारण अक्षर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: संयोजन वर्तुल उच्चारण (U+0302)"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() विधि

ऐक्सेंट अक्षर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## टिप्पणी

उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## देखें

* क्लास [MathAccent](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)