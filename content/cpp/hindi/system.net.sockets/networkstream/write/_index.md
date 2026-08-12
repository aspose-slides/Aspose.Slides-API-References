---
title: Write()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट बाइट एरे से निर्दिष्ट उप-श्रेणी के बाइट्स को स्ट्रीम में लिखता है।
type: docs
weight: 209
url: /hi/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

निर्दिष्ट बाइट एरे से निर्दिष्ट उप-श्रेणी के बाइट्स को स्ट्रीम में लिखता है।

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | बाइट्स लिखने के लिए वाली एरे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | लिखने के लिए उप-श्रेणी में तत्वों की संख्या। |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) मेथड

निर्दिष्ट बाइट एरे से निर्दिष्ट उप-श्रेणी के बाइट्स को स्ट्रीम में लिखता है।

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | बाइट्स लिखने के लिए वाली एरे व्यू। |
| offset | **int32_t** | लिखने के लिए उप-श्रेणी के शुरू होने वाले तत्व का 0-आधारित इंडेक्स **buffer** में। |
| size | **int32_t** | लिखने के लिए उप-श्रेणी में तत्वों की संख्या। |

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [NetworkStream](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)