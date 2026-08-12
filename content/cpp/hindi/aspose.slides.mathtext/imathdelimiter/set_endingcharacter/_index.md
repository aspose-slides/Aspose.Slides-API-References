---
title: set_EndingCharacter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Delimiter Ending Character समाप्ति, या क्लोज़िंग, डिलीमीटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलीमीटर वे समावेशी अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेसेस। डिफ़ॉल्ट: ')'."
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) विधि

Delimiter Ending Character समाप्ति, या क्लोजिंग, डिलीमीटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलीमीटर वे समावेशी अक्षर होते हैं जैसे कि कोष्ठक, ब्रैकेट, और ब्रेसेज। डिफ़ॉल्ट: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## देखें

* क्लास [IMathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)