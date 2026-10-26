---
title: Enclose()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य के रूप में फ्रेम करके और एक विच्छेदक अक्षर द्वारा अलग करके लपेटता है
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) मेथड

इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य रूप में फ्रेम करके और विभाजक अक्षर के साथ अलग करके लपेटता है।

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char16_t | आरंभिक अक्षर (आमतौर पर बायां कोष्ठक) |
| endingCharacter | char16_t | समाप्ति अक्षर (आमतौर पर दायां कोष्ठक) |
| separatorCharacter | char16_t | विभाजक अक्षर |

### रिटर्न वैल्यू

टाइप [IMathDelimiter](../../imathdelimiter/) का गणितीय तत्व जिसमें निर्दिष्ट अक्षर फ्रेमिंग और विभाजक के रूप में शामिल होते हैं।

## टिप्पणियाँ

उदाहरण:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## और देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [IMathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)