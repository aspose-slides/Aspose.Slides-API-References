---
title: TransformBlock()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डेटा के ब्लॉक को प्रोसेस करता है और डेटा को आउटपुट एरे में कॉपी करता है।
type: docs
weight: 1
url: /hi/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) मेथड

डेटा के ब्लॉक को प्रोसेस करता है और डेटा को आउटपुट एरे में कॉपी करता है।

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) डेटा पढ़ने के लिए। |
| inputOffset | int | इनपुट बफ़र ऑफ़सेट। |
| inputCount | int | प्रोसेस करने के लिए बाइट्स की संख्या। |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा कॉपी करने के लिए आउटपुट बफ़र; कोई कॉपी नहीं करने के लिए nullptr। |
| outputOffset | int | आउटपुट बफ़र ऑफ़सेट। |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)