---
title: TransformBlock()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेटा के ब्लॉक को प्रोसेस करता है और डेटा को आउटपुट ऐरे में कॉपी करता है।
type: docs
weight: 53
url: /hi/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) मेथड

डेटा का ब्लॉक प्रोसेस करता है और डेटा को आउटपुट ऐरे में कॉपी करता है।

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से डेटा पढ़ने के लिए। |
| inputOffset | **int32_t** | इनपुट बफ़र ऑफ़सेट। |
| inputCount | **int32_t** | प्रोसेस करने के लिए बाइट्स की संख्या। |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा कॉपी करने के लिए आउटपुट बफ़र; कॉपी न करने के लिए nullptr। |
| outputOffset | **int32_t** | आउटपुट बफ़र ऑफ़सेट। |

### रिटर्न वैल्यू

लिहे गये बाइट्स की संख्या।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ToBase64Transform](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)