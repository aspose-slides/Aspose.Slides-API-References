---
title: Read()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।
type: docs
weight: 183
url: /hi/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट ऐरे। |
| offset | **int32_t** | **buffer** में लेखन शुरू करने के लिए 0-आधारित स्थिति। |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या। |

### वापसी मान

पढ़े गए बाइट्स की संख्या।

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है।

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट ऐरे व्यू। |
| offset | **int32_t** | **buffer** में लेखन शुरू करने के लिए 0-आधारित स्थिति। |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या। |

### वापसी मान

पढ़े गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)