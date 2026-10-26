---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API संदर्भ
description: URI फ्रैगमेंट को एन्कोड करता है।
type: docs
weight: 66
url: /hi/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) मेथड

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | एन्कोड करने हेतु URI फ्रैगमेंट। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) मेथड

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | एन्कोड करने हेतु URI फ्रैगमेंट। |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिये एन्कोडिंग। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) मेथड

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु URI फ्रैगमेंट। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु URI फ्रैगमेंट। |
| offset | **int32_t** | दिए गए बाइट एरे में ऑफ़सेट। |
| count | **int32_t** | पढ़ने के लिये बाइट्स की संख्या। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## संबंधित देखें

* टाइपडेफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [HttpUtility](../)
* क्लास [Encoding](../../../system.text/encoding/)
* नामस्थान [System::Web](../../)
* लाइब्रेरी [Aspose.Slides](../../../)