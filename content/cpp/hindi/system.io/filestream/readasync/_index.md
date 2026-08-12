---
title: ReadAsync()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला को असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है।
type: docs
weight: 196
url: /hi/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) विधि

वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला को असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है।

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | पढ़े गए बाइट्स को लिखने के लिए बाइट ऐरे। |
| offset | **int32_t** | **buffer** में लिखना शुरू करने के लिए 0-आधारित स्थिति। |
| count | **int32_t** | पढ़ने के बाइट्स की संख्या। |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्दीकरण अनुरोधों की निगरानी के लिए टोकन। |

### रिटर्न मान

एक टास्क जो असिंक्रोनस पढ़ने की ऑपरेशन का प्रतिनिधित्व करता है। TResult पैरामीटर का मान बफर में पढ़े गए कुल बाइट्स की संख्या दर्शाता है। यदि वर्तमान में उपलब्ध बाइट्स की संख्या अनुरोधित संख्या से कम है तो परिणाम मान अनुरोधित बाइट्स की संख्या से कम हो सकता है, या यदि स्ट्रीम का अंत पहुंच गया हो तो यह 0 (शून्य) हो सकता है।

## संबंधित देखें

* टाइपडिफ [RTaskPtr](../../../system/rtaskptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [FileStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)