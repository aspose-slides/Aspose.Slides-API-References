---
title: get_SeparatorCharacter()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'."
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() मेथड

Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## संबंधित देखें

* वर्ग [MathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)