---
title: Accent()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस तत्व के शीर्ष पर एक अक्षर के रूप में एक उच्चारण चिह्न सेट करता है
type: docs
weight: 196
url: /hi/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) मेथड

इस तत्व के शीर्ष पर एक अक्षर के रूप में एक उच्चारण चिह्न सेट करता है

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| accentCharacter | char16_t | उच्चारण अक्षर। मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा के भीतर होना चाहिए। |

### रिटर्न वैल्यू

टाइप [IMathAccent](../../imathaccent/) की नई इंस्टेंस

## टिप्पणियाँ

Example: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathAccent](../../imathaccent/)
* क्लास [MathElementBase](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)