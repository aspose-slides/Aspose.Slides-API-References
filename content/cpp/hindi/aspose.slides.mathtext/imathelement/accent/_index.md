---
title: Accent()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस तत्व के शीर्ष पर एक अक्षर के रूप में एक्सेंट मार्क सेट करता है
type: docs
weight: 209
url: /hi/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) विधि

एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक अक्षर)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| accentCharacter | char16_t | एक्सेंट अक्षर। मान को (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। |

### रिटर्न मान

प्रकार [IMathAccent](../../imathaccent/) की नई इंस्टेंस

## टिप्पणी

उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathAccent](../../imathaccent/)
* क्लास [IMathElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)