---
title: set_Character()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक्सेंट वर्ण मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: संयोजित बिंदु एक्सेंट (U+0302)"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) मेथड


एक्सेंट वर्ण मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: संयोजित सरक्युलर एक्सेंट (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## देखें

* क्लास [IMathAccent](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)