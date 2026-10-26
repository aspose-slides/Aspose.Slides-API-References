---
title: set_Character()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा के भीतर होना चाहिए डिफ़ॉल्ट मान: कॉम्बाइनिंग सर्क़ुमफ़्लेक्स एक्सेंट (U+0302)"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) मेथड

एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या(U+20D0\\u2013U+20EF) के दायरे में होना चाहिए। डिफ़ॉल्ट मान: कॉम्बाइनिंग सर्क़ुमफ़्लेक्स एक्सेंट (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## टिप्पणी

उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## देखें

* क्लास [MathAccent](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)