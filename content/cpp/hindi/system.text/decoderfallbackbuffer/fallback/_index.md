---
title: Fallback()
second_title: Aspose.Slides for C++ API संदर्भ
description: वास्तविक फॉलबैक प्रक्रिया को लागू करता है।
type: docs
weight: 14
url: /hi/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) विधि

वास्तविक फॉलबैक प्रक्रिया को लागू करता है।

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) बाइट्स का वह भाग जिसमें वह बाइट भी शामिल है जिसे डिकोडर डिकोड करने में विफल रहता है। |
| index | int | [Index](../../../system/index/) वह बाइट जिसका त्रुटि उत्पन्न हुई। |

### रिटर्न वैल्यू

यदि बफ़र अनजान बाइट्स को प्रोसेस करता है तो सत्य, अन्यथा यदि वह उन्हें अनदेखा करता है तो असत्य।

## सम्बंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)