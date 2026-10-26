---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा के अंतिम ब्लॉक को प्रोसेस करता है और आउटपुट मान की गणना करता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) विधि

डेटा के अंतिम ब्लॉक को प्रोसेस करता है और आउटपुट मान की गणना करता है।

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) डेटा पढ़ने के लिए। |
| inputOffset | int | इनपुट बफ़र ऑफ़सेट। |
| inputCount | int | प्रोसेस करने के लिए बाइट्स की संख्या। |

### वापसी मान

पूरे इनपुट अनुक्रम के लिए गणना किया गया आउटपुट।

## देखें

* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)