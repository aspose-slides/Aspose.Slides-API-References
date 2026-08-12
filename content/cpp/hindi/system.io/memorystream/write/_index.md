---
title: Write()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है।
type: docs
weight: 92
url: /hi/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है।

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे |
| offset | **int32_t** | **buffer** में 0-आधारित सूचकांक, जहाँ उप-रेंज लिखना शुरू होता है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है।

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे व्यू |
| offset | **int32_t** | **buffer** में 0-आधारित सूचकांक, जहाँ उप-रेंज लिखना शुरू होता है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)