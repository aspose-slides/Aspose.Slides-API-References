---
title: Seek()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति निर्धारित करता है।
type: docs
weight: 209
url: /hi/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) मेथड

वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है।

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| offset | **int64_t** | बाइट ऑफसेट **origin** द्वारा निर्दिष्ट स्थिति के सापेक्ष। |
| origin | [SeekOrigin](../../seekorigin/) | स्थिति निर्दिष्ट करता है जिससे और दिशा जिसके प्रति ऑफसेट की गणना की जाती है। |

### वापसी मान

स्ट्रीम की नई स्थिति।

## देखें

* Enum [SeekOrigin](../../seekorigin/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)