---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट बाइट्स की संख्या को अंतर्निहित स्ट्रीम से पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 53
url: /hi/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट्स की संख्या को अंतर्निहित स्ट्रीम से पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट्स की संख्या को अंतर्निहित स्ट्रीम से पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [BufferedStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)