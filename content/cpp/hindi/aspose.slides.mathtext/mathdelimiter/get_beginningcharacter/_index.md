---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Delimiter Beginning Character प्रारंभ, या खोलने वाले, डिलिमीटर वर्ण को निर्दिष्ट करता है। गणितीय डिलिमिटर ऐसे समावेशी वर्ण होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट: '('।"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() विधि

Delimiter Beginning Character प्रारंभ, या खोलने वाला, डिलिमीटर वर्ण निर्दिष्ट करता है। गणितीय डिलिमीटर ऐसे समावेशी वर्ण होते हैं जैसे कोष्ठक, ब्रेस, और घुंघराले ब्रैकेट। डिफ़ॉल्ट: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## टिप्पणी

उदाहरण:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## देखें

* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)