---
title: get_Character()
second_title: Aspose.Slides for C++ API संदर्भ
description: "समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (नीचे की कर्ली ब्रैकेट)"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() method


समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (नीचे का कर्ली ब्रेस)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// नीचे का कोष्ठक
```

## देखें

* क्लास [IMathGroupingCharacter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)