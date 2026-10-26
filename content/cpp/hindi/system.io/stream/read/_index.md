---
title: Read()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 27
url: /hi/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे व्यू |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | स्टैक एरे का आकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट स्टैक एरे |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## Stream::Read(const System::Span\<uint8_t\>\&) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है।

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट स्पैन |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## संबंधित देखें

* टाइपडैफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Stream](../)
* क्लास [Span](../../../system/span/)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)