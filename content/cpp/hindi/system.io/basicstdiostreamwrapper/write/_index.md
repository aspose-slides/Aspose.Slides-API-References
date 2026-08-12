---
title: Write()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट उपसमुच्चय को स्ट्रीम में लिखता है, अन्यथा निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट उपसमुच्चय को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम में लिखता है।
type: docs
weight: 79
url: /hi/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि


यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट उपसमुच्चय को स्ट्रीम में लिखता है, अन्यथा निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट उपसमुच्चय को char_type प्रकार में परिवर्तित करता है और फिर परिणाम को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे |
| offset | **int32_t** | **buffer** में तत्व का शून्य-आधारित सूचकांक जहाँ लिखने के लिए उपसमुच्चय शुरू होता है |
| count | **int32_t** | लिखने के लिए उपसमुच्चय में तत्वों की संख्या |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि


निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट उपसमुच्चय को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे व्यू |
| offset | **int32_t** | **buffer** में तत्व का शून्य-आधारित सूचकांक जहाँ लिखने के लिए उपसमुच्चय शुरू होता है |
| count | **int32_t** | लिखने के लिए उपसमुच्चय में तत्वों की संख्या |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [BasicSTDIOStreamWrapper](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)