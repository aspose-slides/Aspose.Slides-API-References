---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API संदर्भ
description: बाइट्स ऐरे से URI फ्रैगमेंट को डिकोड करता है।
type: docs
weight: 14
url: /hi/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) विधि

बाइट्स ऐरे से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड किया गया URI फ्रैगमेंट। |

### रिटर्न मान

डिकोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlDecodeToBytes(const String\&) विधि

बाइट्स स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | एन्कोड किया गया URI फ्रैगमेंट। |

### रिटर्न मान

डिकोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) विधि

स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | एन्कोड किया गया URI फ्रैगमेंट। |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिए एन्कोडिंग। |

### रिटर्न मान

डिकोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

बाइट्स ऐरे से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड किया गया URI फ्रैगमेंट। |
| offset | **int32_t** | दिए गए बाइट ऐरे में ऑफ़सेट। |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या। |

### रिटर्न मान

डिकोड किया गया URI फ्रैगमेंट।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [HttpUtility](../)
* क्लास [String](../../../system/string/)
* क्लास [Encoding](../../../system.text/encoding/)
* नेमस्पेस [System::Web](../../)
* लाइब्रेरी [Aspose.Slides](../../../)