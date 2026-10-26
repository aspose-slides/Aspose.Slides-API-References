---
title: Fallback()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एन्कोडिंग विफलता को संभालता है।
type: docs
weight: 27
url: /hi/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) विधि

एन्कोडिंग विफलता को संभालता है।

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| charUnknown | char_t | अज्ञात अक्षर; अनदेखा किया गया। |
| index | int | अज्ञात अक्षरों का ऑफसेट; अनदेखा किया गया। |

### रिटर्न मान

वास्तव में कभी रिटर्न नहीं करता, बल्कि एक्सेप्शन फेंकता है।

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) विधि

एन्कोडिंग विफलता को संभालता है।

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| charUnknownHigh | char_t | त्रुटि उत्पन्न करने वाले सरोगेट पेयर का उच्च भाग। |
| charUnknownLow | char_t | त्रुटि उत्पन्न करने वाले सरोगेट पेयर का निम्न भाग। |
| index | int | अज्ञात अक्षर का ऑफसेट; अनदेखा किया गया। |

### रिटर्न मान

वास्तव में कभी रिटर्न नहीं करता, बल्कि एक्सेप्शन फेंकता है।

## संबंधित देखें

* क्लास [EncoderExceptionFallbackBuffer](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)