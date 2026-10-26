---
title: Write()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट सबरेंज को स्ट्रीम में लिखता है, अन्यथा निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट सबरेंज को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम में लिखता है। समर्थित नहीं!
type: docs
weight: 79
url: /hi/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट उप-रेंज को स्ट्रीम में लिखता है, अन्यथा निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट उप-रेंज को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम में लिखता है। समर्थित नहीं!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे। |
| offset | **int32_t** | **buffer** में उस तत्व का 0-आधारित सूचकांक जहाँ लिखने के लिए उप-रेंज शुरू होती है। |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या। |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट उप-रेंज को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स को सम्मिलित करने वाला एरे व्यू |
| offset | **int32_t** | **buffer** में उस तत्व का 0-आधारित सूचकांक जहाँ लिखने के लिए उप-रेंज शुरू होती है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [BasicSTDIStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)