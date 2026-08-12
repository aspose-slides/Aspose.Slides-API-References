---
title: WriteAsync()
second_title: Aspose.Slides for C++ API संदर्भ
description: असिंक्रोनस रूप से वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या के द्वारा इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है।
type: docs
weight: 261
url: /hi/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) विधि

असिंक्रोनस रूप से वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या के द्वारा इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है।

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लेखन के लिए बाइट्स वाला एरे। |
| offset | **int32_t** | **buffer** में लिखने के लिए सबरेंज के शुरू होने का 0-आधारित सूचकांक। |
| count | **int32_t** | लेखन के लिए उप-श्रेणी में तत्वों की संख्या। |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्दीकरण अनुरोधों की निगरानी के लिए टोकन। |

### रिटर्न वैल्यू

एक कार्य (टास्क) जो असिंक्रोनस लेखन ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [FileStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)