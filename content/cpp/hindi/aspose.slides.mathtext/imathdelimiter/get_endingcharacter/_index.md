---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वह घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और ब्रेसेज़। डिफ़ॉल्ट: ')'."
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() मेथड

डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और ब्रेसेज़। डिफ़ॉल्ट: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## ऊपर देखें

* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)