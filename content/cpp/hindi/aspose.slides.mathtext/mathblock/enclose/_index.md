---
title: Enclose()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में संलग्न करता है
type: docs
weight: 222
url: /hi/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) मेथड

इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में संलग्न करता है

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | प्रारम्भिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char16_t | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |

### रिटर्न वैल्यू

टाइप [IMathDelimiter](../../imathdelimiter/) का मैथ तत्व जो निर्दिष्ट अक्षरों को फ्रेमिंग के रूप में शामिल करता है
## टिप्पणी

उदाहरण: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) मेथड

इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में संलग्न करता है और एक विभाजक अक्षर से अलग करता है

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | प्रारम्भिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char16_t | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |
| separatorCharacter | char16_t | विभाजक अक्षर |

### रिटर्न वैल्यू

टाइप [IMathDelimiter](../../imathdelimiter/) का मैथ तत्व जो निर्दिष्ट अक्षरों को फ्रेमिंग और विभाजक के रूप में शामिल करता है
## टिप्पणी

उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)