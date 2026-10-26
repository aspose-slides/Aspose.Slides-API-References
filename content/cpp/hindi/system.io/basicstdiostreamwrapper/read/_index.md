---
title: Read()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में अक्षर पढ़ता है और उन्हें uint8_t प्रकार में परिवर्तित करता है। पढ़ने के परिणाम को निर्दिष्ट बाइट एरे में लिखता है।
type: docs
weight: 66
url: /hi/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

यदि रैपिंग मोड बाइनरी है, तो स्ट्रिम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में कैरेक्टर्स पढ़ता है और उन्हें **uint8_t** प्रकार में परिवर्तित करता है। पढ़ने के परिणाम को निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ से लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### लौटाने मान

पढ़े गए बाइट्स या कैरेक्टर्स की संख्या

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

स्ट्रिम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे व्यू |
| offset | **int32_t** | **buffer** में 0-आधारित स्थिति जहाँ से लिखना शुरू करना है |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### लौटाने मान

पढ़ी गई बाइट्स की संख्या

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [BasicSTDIOStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)