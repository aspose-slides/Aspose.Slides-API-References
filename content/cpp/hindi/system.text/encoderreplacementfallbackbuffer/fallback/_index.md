---
title: Fallback()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एन्कोडिंग विफलता को संभालता है।
type: docs
weight: 27
url: /hi/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) विधि

एन्कोडिंग विफलता को संभालता है।

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| charUnknown | char_t | अज्ञात अक्षर; अनदेखा किया गया। |
| index | int | अज्ञात अक्षर की स्थिति; अनदेखा किया गया। |

### रिटर्न वैल्यू

यदि प्रतिस्थापन स्ट्रिंग प्रदान की गई है और वह खाली नहीं है तो true, अन्यथा false।

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) विधि

एन्कोडिंग विफलता को संभालता है।

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| charUnknownHigh | char_t | त्रुटि उत्पन्न करने वाली सर्जेट जोड़ी का उच्च भाग। |
| charUnknownLow | char_t | त्रुटि उत्पन्न करने वाली सर्जेट जोड़ी का निचला भाग। |
| index | int | अज्ञात अक्षर की स्थिति; अनदेखा किया गया। |

### रिटर्न वैल्यू

यदि प्रतिस्थापन स्ट्रिंग प्रदान की गई है और वह खाली नहीं है तो true, अन्यथा false।

## संबंधित देखें

* क्लास [EncoderReplacementFallbackBuffer](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)