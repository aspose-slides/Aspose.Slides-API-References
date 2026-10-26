---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिलिमिटर शुरुआत अक्षर प्रारम्भ, या खोलने वाला, डिलिमिटर अक्षर निर्दिष्ट करता है। गणितीय डिलिमिटर वे सीमावर्ती अक्षर होते हैं जैसे कोष्ठक, वर्ग कोष्ठक और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: '('."
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) विधि

डिलिमिटर शुरुआत अक्षर प्रारम्भ, या खोलने वाला, डिलिमिटर अक्षर निर्दिष्ट करता है। गणितीय डिलिमिटर वह सीमावर्ती अक्षर होते हैं जैसे कोष्ठक, वर्ग कोष्ठक, और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## टिप्पणी

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## और देखें

* क्लास [IMathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)