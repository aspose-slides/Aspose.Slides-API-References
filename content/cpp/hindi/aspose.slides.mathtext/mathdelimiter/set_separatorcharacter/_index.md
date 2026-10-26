---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो delimiter object में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'."
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) विधि

Delimiter Separator Character निर्दिष्ट करता है वह अक्षर जो delimiter object में arguments को अलग करता है। डिफ़ॉल्ट: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## संबंधित देखें

* क्लास [MathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)