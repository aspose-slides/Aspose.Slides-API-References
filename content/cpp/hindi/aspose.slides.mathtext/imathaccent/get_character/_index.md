---
title: get_Character()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक्सेंट वर्ण मान (U+0300\\u2013U+036F) या(U+20D0\\u2013U+20EF) की सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() विधि


एक्सेंट वर्ण का मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## संबंधित देखें

* क्लास [IMathAccent](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)