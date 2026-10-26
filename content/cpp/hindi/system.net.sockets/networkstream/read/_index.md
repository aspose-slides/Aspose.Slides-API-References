---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।
type: docs
weight: 196
url: /hi/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि


निर्दिष्ट स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | वह बाइट ऐरे जहाँ पढ़े गए बाइट्स लिखे जाएँगे। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट्स में ऑफसेट। |
| size | **int32_t** | पढ़ने के लिए बाइट्स की संख्या। |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या।

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि


निर्दिष्ट स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट ऐरे व्यू |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| size | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## देखें भी

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* कक्षा [NetworkStream](../)
* नामस्थान [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)