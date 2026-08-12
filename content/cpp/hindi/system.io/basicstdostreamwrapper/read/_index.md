---
title: Read()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में अक्षर पढ़ता है और उन्हें uint8_t प्रकार में परिवर्तित करता है। पढ़ी गई सामग्री को निर्दिष्ट बाइट एरे में लिखता है। समर्थित नहीं है!
type: docs
weight: 66
url: /hi/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में अक्षर पढ़ता है और उन्हें **uint8_t** प्रकार में परिवर्तित करता है। पढ़ी गई सामग्री को निर्दिष्ट बाइट एरे में लिखता है। समर्थित नहीं है!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### Return Value

पढ़े गए बाइट्स या अक्षरों की संख्या

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) मेथड

स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है।

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट एरे व्यू |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या |

### Return Value

पढ़े गए बाइट्स की संख्या

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)