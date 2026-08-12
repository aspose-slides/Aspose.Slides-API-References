---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिलिमिटर समाप्ति वर्ण समाप्ति, या समापन, डिलिमिटर वर्ण को निर्दिष्ट करता है। गणितीय डिलिमिटर वे सम्मिलित करने वाले वर्ण होते हैं जैसे कोष्ठक, वर्ग कोष्ठक, और कर्ली ब्रेसेस। डिफ़ॉल्ट: ')'."
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) विधि

डिलिमिटर समाप्ति वर्ण समाप्ति, या समापन, डिलिमिटर वर्ण को निर्दिष्ट करता है। गणितीय डिलिमिटर वे सम्मिलित करने वाले वर्ण होते हैं जैसे कोष्ठक, वर्ग कोष्ठक, और कर्ली ब्रेसेस। डिफ़ॉल्ट: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
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