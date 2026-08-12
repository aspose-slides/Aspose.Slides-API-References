---
title: Read()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में कैरेक्टर पढ़ता है और उन्हें uint8_t प्रकार में परिवर्तित करता है। पढ़ने के परिणाम को निर्दिष्ट बाइट एरे में लिखा जाता है।
type: docs
weight: 66
url: /hi/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में कैरेक्टर पढ़ता है और उन्हें **uint8_t** प्रकार में परिवर्तित करता है। पढ़ने का परिणाम निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में 0-आधारित स्थान जहाँ से लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### वापसी मान

बाइट्स या कैरेक्टर की पढ़ी गई संख्या

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स लिखने के लिए बाइट एरे व्यू |
| offset | **int32_t** | **buffer** में 0-आधारित स्थान जहाँ से लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### वापसी मान

पढ़े गए बाइट्स की संख्या

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [BasicSTDIStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)