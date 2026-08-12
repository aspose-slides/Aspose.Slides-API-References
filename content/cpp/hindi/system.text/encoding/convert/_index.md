---
title: Convert()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दो एन्कोडिंग्स के बीच बाइट्स को बदलता है।
type: docs
weight: 378
url: /hi/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) विधि

दो एन्कोडिंग्स के बीच बाइट्स को बदलता है।

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | स्रोत एन्कोडिंग। |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | गंतव्य एन्कोडिंग। |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | बदलने के लिए बाइट्स। |

### वापसी मान

बदले हुए बाइट्स।

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) विधि

दो एन्कोडिंग्स के बीच बाइट्स को बदलता है।

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | स्रोत एन्कोडिंग। |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | गंतव्य एन्कोडिंग। |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | बदलने के लिए बाइट्स। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस का आकार। |

### वापसी मान

बदले हुए बाइट्स।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [Encoding](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)