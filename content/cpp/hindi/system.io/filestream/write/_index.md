---
title: Write()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है।
type: docs
weight: 248
url: /hi/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है।

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाला एरे। |
| offset | **int32_t** | **buffer** में उस तत्व का 0-आधारित इंडेक्स जहाँ से लिखने की उप-श्रेणी शुरू होती है। |
| count | **int32_t** | लिखने के लिए उप-श्रेणी में तत्वों की संख्या। |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है।

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स को समाहित करने वाला एरे व्यू। |
| offset | **int32_t** | **buffer** में उस तत्व का 0-आधारित इंडेक्स जहाँ से लिखने की उप-श्रेणी शुरू होती है। |
| count | **int32_t** | लिखने के लिए उप-श्रेणी में तत्वों की संख्या। |

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [FileStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)