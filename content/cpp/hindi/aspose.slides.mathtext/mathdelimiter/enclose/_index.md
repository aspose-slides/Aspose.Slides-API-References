---
title: Enclose()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट वर्णों, जैसे कोष्ठक या अन्य वर्ण, को फ्रेमिंग के रूप में उपयोग करके एक गणितीय तत्व को घेरता है
type: docs
weight: 170
url: /hi/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) विधि

निर्दिष्ट वर्णों (जैसे कोष्ठक या अन्य वर्ण) को फ्रेमिंग के रूप में उपयोग करके गणितीय तत्व को घेरता है।

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char16_t | प्रारंभिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char16_t | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |

### रिटर्न मान

*beginningCharacter* और *endingCharacter* यदि null हैं, तो संबंधित गुणों को केवल मान सौंपे जाते हैं और कोई नया ऑब्जेक्ट नहीं बनाया जाता (यह उदाहरण वापस करता है)। अन्यथा, Delimiter प्रकार का नया गणितीय तत्व लौटाता है जिसमें निर्दिष्ट वर्ण फ्रेमिंग के रूप में शामिल होते हैं और इस [MathDelimiter](../) का उदाहरण उसके भीतर फ्रेम किया जाता है।

## टिप्पणी



उदाहरण: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [MathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)