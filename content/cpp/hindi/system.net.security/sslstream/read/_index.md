---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रीम से निर्दिष्ट संख्या में बाइट्स को पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 391
url: /hi/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े हुए बाइट्स को लिखने के लिये बाइट एरे |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिये बाइट्स की संख्या |

### वापसी मान

पढ़े गए बाइट्स की संख्या

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े हुए बाइट्स को लिखने के लिये बाइट एरे |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिये बाइट्स की संख्या |

### वापसी मान

पढ़े गए बाइट्स की संख्या

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [SslStream](../)
* नेमस्पेस [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)