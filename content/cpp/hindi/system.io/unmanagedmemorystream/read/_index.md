---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 144
url: /hi/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ से लिखना शुरू किया जाए |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) मेथड

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे व्यू |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ से लिखना शुरू किया जाए |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [UnmanagedMemoryStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)