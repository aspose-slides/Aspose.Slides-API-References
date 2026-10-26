---
title: get_EndingCharacter()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "Delimiter Ending Character समाप्ति या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर ऐसे बंद करने वाले अक्षर होते हैं जैसे कोष्ठक, वर्गकोष्ठक और कर्ली ब्रेसेस। डिफ़ॉल्ट: ')'."
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() मेथड

डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वह बंद करने वाले अक्षर होते हैं जैसे कोष्ठक, वर्ग कोष्ठक और कर्ली ब्रैकेट। डिफ़ॉल्ट: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## संबंधित देखें

* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)