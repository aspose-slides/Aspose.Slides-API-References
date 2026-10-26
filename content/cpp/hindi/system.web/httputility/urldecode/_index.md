---
title: UrlDecode()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है।
type: docs
weight: 1
url: /hi/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) विधि

स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) | एन्कोड किया गया URI फ़्रैगमेंट। |

### रिटर्न मान

डिकोड किया गया URI फ़्रैगमेंट।

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) विधि

स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) | एन्कोड किया गया URI फ़्रैगमेंट। |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | उपयोग करने के लिये एन्कोडिंग। |

### रिटर्न मान

डिकोड किया गया URI फ़्रैगमेंट।

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) विधि

बाइट एरे से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड किया गया URI फ़्रैगमेंट। |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिये एन्कोडिंग। |

### रिटर्न मान

डिकोड किया गया URI फ़्रैगमेंट।

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) विधि

बाइट एरे से URI फ्रैगमेंट को डिकोड करता है।

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड किया गया URI फ़्रैगमेंट। |
| offset | **int32_t** | दिए गये बाइट एरे में ऑफ़सेट। |
| count | **int32_t** | पढ़ने के लिये बाइट्स की संख्या। |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिये एन्कोडिंग। |

### रिटर्न मान

डिकोड किया गया URI फ़्रैगमेंट।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* वर्ग [String](../../../system/string/)
* वर्ग [HttpUtility](../)
* वर्ग [Encoding](../../../system.text/encoding/)
* नामस्थान [System::Web](../../)
* लाइब्रेरी [Aspose.Slides](../../../)