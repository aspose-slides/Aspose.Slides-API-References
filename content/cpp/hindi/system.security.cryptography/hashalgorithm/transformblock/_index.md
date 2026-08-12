---
title: TransformBlock()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: डेटा के ब्लॉक को प्रोसेस करता है और डेटा को आउटपुट एरे में कॉपी करता है।
type: docs
weight: 66
url: /hi/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


डेटा के ब्लॉक को प्रोसेस करता है और डेटा को आउटपुट एरे में कॉपी करता है।

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से डेटा पढ़ने के लिए। |
| inputOffset | int | इनपुट बफ़र ऑफसेट। |
| inputCount | int | प्रोसेस करने के लिए बाइट्स की संख्या। |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा को कॉपी करने के लिए आउटपुट बफ़र; कोई कॉपी नहीं करने के लिए nullptr। |
| outputOffset | int | आउटपुट बफ़र ऑफसेट। |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## देखें भी

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [HashAlgorithm](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)