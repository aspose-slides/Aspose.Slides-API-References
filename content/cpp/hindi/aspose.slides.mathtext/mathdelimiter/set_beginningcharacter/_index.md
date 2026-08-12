---
title: set_BeginningCharacter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Delimiter Beginning Character शुरुआत, या खुलने वाला, डिलिमिटर अक्षर निर्दिष्ट करता है। गणितीय डिलिमिटर वे संलग्न करने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और ब्रेस। डिफ़ॉल्ट: '('."
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) विधि

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. गणितीय डिलिमिटर वे सम्मिलित अक्षर होते हैं जैसे कि कोष्ठक, ब्रैकेट और ब्रेसेज। डिफ़ॉल्ट: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## देखें भी

* वर्ग [MathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)