---
title: Write()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे से निर्दिष्ट उप-सीमा के बाइट्स को स्ट्रीम पर लिखता है, अन्यथा निर्दिष्ट बाइट एरे से निर्दिष्ट उप-सीमा के बाइट्स को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम पर लिखता है।
type: docs
weight: 79
url: /hi/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे से निर्दिष्ट उप-सीमा के बाइट्स को स्ट्रीम पर लिखता है, अन्यथा निर्दिष्ट बाइट एरे से निर्दिष्ट उप-सीमा के बाइट्स को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम पर लिखता है।

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे |
| offset | **int32_t** | एक 0-आधारित सूचकांक **buffer** में जहाँ लिखने की उप-सीमा शुरू होती है |
| count | **int32_t** | लिखने के लिए उप-सीमा में तत्वों की संख्या |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट एरे से निर्दिष्ट उप-सीमा के बाइट्स को स्ट्रीम पर लिखता है।

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाले एरे व्यू |
| offset | **int32_t** | एक 0-आधारित सूचकांक **buffer** में जहाँ लिखने की उप-सीमा शुरू होती है |
| count | **int32_t** | लिखने के लिए उप-सीमा में तत्वों की संख्या |

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [BasicSTDOStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)