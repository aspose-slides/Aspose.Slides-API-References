---
title: Write()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-श्रेणी को अंतर्निहित स्ट्रीम में लिखता है।
type: docs
weight: 66
url: /hi/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-श्रेणी को अंतर्निहित स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिये बाइट्स को सम्मिलित करने वाला ऐरे |
| offset | **int32_t** | **buffer** में तत्व का 0-आधारित सूचकांक जहाँ लिखने के लिये उप-श्रेणी शुरू होती है |
| count | **int32_t** | लिखने के लिये उप-श्रेणी में तत्वों की संख्या |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-श्रेणी को अंतर्निहित स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिये बाइट्स को सम्मिलित करने वाला ऐरे |
| offset | **int32_t** | **buffer** में तत्व का 0-आधारित सूचकांक जहाँ लिखने के लिये उप-श्रेणी शुरू होती है |
| count | **int32_t** | लिखने के लिये उप-श्रेणी में तत्वों की संख्या |

## सन्दर्भ

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [BufferedStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)