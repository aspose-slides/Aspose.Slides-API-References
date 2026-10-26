---
title: Fallback()
second_title: Aspose.Slides for C++ API संदर्भ
description: वास्तविक फॉलबैक प्रक्रिया को लागू करता है।
type: docs
weight: 14
url: /hi/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) मेथड

वास्तविक फॉलबैक प्रक्रिया को लागू करता है।

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| charUnknown | char_t | कैरेक्टर एन्कोडर एन्कोड नहीं कर पाता। |
| index | int | [Index](../../../system/index/) त्रुटि उत्पन्न करने वाले अक्षर का। |

### रिटर्न वैल्यू

बफ़र अज्ञात अक्षरों को प्रोसेस करता है तो True, अन्यथा यदि यह उन्हें अनदेखा करता है तो false।

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) मेथड

वास्तविक फॉलबैक प्रक्रिया को लागू करता है।

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| charUnknownHigh | char_t | त्रुटि उत्पन्न करने वाले सरोगेट पेयर का हाई भाग। |
| charUnknownLow | char_t | त्रुटि उत्पन्न करने वाले सरोगेट पेयर का लो भाग। |
| index | int | [Index](../../../system/index/) त्रुटि उत्पन्न करने वाले अक्षर का। |

### रिटर्न वैल्यू

बफ़र अज्ञात अक्षरों को प्रोसेस करता है तो True, अन्यथा यदि यह उन्हें अनदेखा करता है तो false।

## संबंधित देखें

* क्लास [EncoderFallbackBuffer](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)