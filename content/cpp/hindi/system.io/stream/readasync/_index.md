---
title: ReadAsync()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला को असिंक्रोनस रूप से पढ़ता है, पढ़े गये बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।
type: docs
weight: 40
url: /hi/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) विधि

वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला को असिंक्रोनस तौर पर पढ़ता है, पढ़े गये बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गये बाइट्स को लिखने के लिए बाइट एरे। |
| offset | **int32_t** | **buffer** में 0-आधारित वह स्थिति जहाँ लिखना शुरू किया जाएगा। |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या। |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्द करने के अनुरोधों की निगरानी करने के लिए टोकन। |

### वापसी मान

एक टास्क जो असिंक्रोनस पढ़ने की प्रक्रिया का प्रतिनिधित्व करता है। TResult पैरामीटर का मान बफ़र में पढ़े गये बाइट्स की कुल संख्या रखता है। परिणाम मान अनुरोधित बाइट्स की संख्या से कम हो सकता है यदि उपलब्ध बाइट्स की संख्या अनुरोधित संख्या से कम है, या यदि स्ट्रीम का अंत पहुँच गया हो तो यह 0 (शून्य) हो सकता है।

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि

वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला को असिंक्रोनस तौर पर पढ़ता है, पढ़े गये बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गये बाइट्स को लिखने के लिए बाइट एरे। |
| offset | **int32_t** | **buffer** में 0-आधारित वह स्थिति जहाँ लिखना शुरू किया जाएगा। |
| count | **int32_t** | पढ़े जाने वाले बाइट्स की संख्या। |

### वापसी मान

एक टास्क जो असिंक्रोनस पढ़ने की प्रक्रिया का प्रतिनिधित्व करता है। TResult पैरामीटर का मान बफ़र में पढ़े गये बाइट्स की कुल संख्या रखता है। परिणाम मान अनुरोधित बाइट्स की संख्या से कम हो सकता है यदि उपलब्ध बाइट्स की संख्या अनुरोधित संख्या से कम है, या यदि स्ट्रीम का अंत पहुँच गया हो तो यह 0 (शून्य) हो सकता है।

## संबंधित देखें

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [Stream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)