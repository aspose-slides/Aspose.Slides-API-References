---
title: Enclose()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: एक गणितीय तत्व को कोष्ठकों में संलग्न करता है
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() विधि

एक गणितीय तत्व को कोष्ठकों में संलग्न करता है

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### रिटर्न वैल्यू

एक [IMathDelimiter](../../imathdelimiter/) प्रकार का गणितीय तत्व जिसमें कोष्ठक शामिल होते हैं

## ध्यान दें



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) विधि

निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य वर्णों में इस तत्व को फ्रेमिंग के रूप में संलग्न करता है

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| beginningCharacter | char16_t | प्रारम्भिक वर्ण (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char16_t | समाप्ति वर्ण (आमतौर पर दायाँ कोष्ठक) |

### रिटर्न वैल्यू

एक [IMathDelimiter](../../imathdelimiter/) प्रकार का गणितीय तत्व जिसमें निर्दिष्ट वर्ण फ्रेमिंग के रूप में शामिल होते हैं

## ध्यान दें



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [IMathElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)