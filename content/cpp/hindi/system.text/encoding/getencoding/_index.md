---
title: GetEncoding()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नाम द्वारा एन्कोडिंग प्राप्त करता है।
type: docs
weight: 508
url: /hi/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) विधि


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) नाम. |

### रिटर्न वैल्यू

[Encoding](../) निर्दिष्ट नाम का।

## Encoding::GetEncoding(int) विधि


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codepage | int | कोडपेज संख्या. |

### रिटर्न वैल्यू

[Encoding](../) निर्दिष्ट कोडपेज का।

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) विधि


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codepage | int | कोडपेज संख्या. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | एन्कोडिंग के लिये उपयोग करने वाला फॉलबैक. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | डिकोडिंग के लिये उपयोग करने वाला फॉलबैक. |

### रिटर्न वैल्यू

[Encoding](../) निर्दिष्ट कोडपेज का।

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) विधि


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) नाम. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | एन्कोडिंग के लिये उपयोग करने वाला फॉलबैक. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | डिकोडिंग के लिये उपयोग करने वाला फॉलबैक. |

### रिटर्न वैल्यू

[Encoding](../) निर्दिष्ट नाम का।

## देखें

* टाइपडिफ [EncodingPtr](../../../system/encodingptr/)
* टाइपडिफ [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* टाइपडिफ [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* क्लास [String](../../../system/string/)
* क्लास [Encoding](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)