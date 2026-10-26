---
title: set_SeparatorCharacter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "डिलिमिटर सेपरेटर कैरेक्टर वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'."
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) विधि


Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## संबंधित देखें

* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)