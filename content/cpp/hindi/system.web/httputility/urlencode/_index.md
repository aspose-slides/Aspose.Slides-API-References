---
title: UrlEncode()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: URI फ्रैगमेंट को एन्कोड करता है।
type: docs
weight: 53
url: /hi/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) विधि

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) | एन्कोड करने के लिए URI फ्रैगमेंट। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) विधि

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) | एन्कोड करने के लिए URI फ्रैगमेंट। |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | उपयोग करने के लिए एन्कोडिंग। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) विधि

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड करने के लिए URI फ्रैगमेंट। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

URI फ्रैगमेंट को एन्कोड करता है।

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एन्कोड करने के लिए URI फ्रैगमेंट। |
| offset | **int32_t** | दिए गए बाइट ऐरे में ऑफसेट। |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या। |

### रिटर्न मान

एन्कोड किया गया URI फ्रैगमेंट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)