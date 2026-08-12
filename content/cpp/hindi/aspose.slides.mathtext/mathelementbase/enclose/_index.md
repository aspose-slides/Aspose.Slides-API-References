---
title: Enclose()
second_title: Aspose.Slides for C++ API संदर्भ
description: गणितीय तत्व को कोष्ठक में संलग्न करता है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() विधि

एक गणितीय तत्व को कोष्ठकों में संलग्न करता है

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### रिटर्न वैल्यू

टाइप [IMathDelimiter](../../imathdelimiter/) का गणितीय तत्व जिसमें कोष्ठक शामिल हैं
## टिप्पणियाँ

उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) विधि

एक गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ़्रेमिंग के रूप में संलग्न करता है

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char16_t | प्रारम्भिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char16_t | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |

### रिटर्न वैल्यू

टाइप [IMathDelimiter](../../imathdelimiter/) का गणितीय तत्व जिसमें निर्दिष्ट अक्षर फ़्रेमिंग के रूप में शामिल हैं
## टिप्पणियाँ

उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [MathElementBase](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)