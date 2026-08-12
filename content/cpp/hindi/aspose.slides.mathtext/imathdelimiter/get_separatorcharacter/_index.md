---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिलिमिटर विभाजक अक्षर वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में आर्ग्यूमेंट्स को अलग करता है। डिफ़ॉल्ट: '|'."
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() विधि

डिलिमिटर विभाजक अक्षर वह अक्षर निर्दिष्ट करता है जो डिलिमिटर वस्तु में आर्ग्यूमेंट्स को अलग करता है। डिफ़ॉल्ट: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## टिप्पणी

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## अन्य देखें

* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)