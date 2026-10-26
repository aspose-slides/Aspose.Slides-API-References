---
title: get_BeginningCharacter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "डिलिमीटर शुरुआत अक्षर प्रारंभ, या खोलने वाले डिलिमीटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर्स ऐसे संलग्न अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट मान: '('."
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() विधि


डिलिमीटर शुरुआत अक्षर डिलिमीटर के शुरुआती या खोलने वाले अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर्स ऐसे संलग्न अक्षर होते हैं जैसे कोष्ठक, ब्रेस और ब्रैकेट। डिफ़ॉल्ट मान: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## देखें

* क्लास [IMathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)