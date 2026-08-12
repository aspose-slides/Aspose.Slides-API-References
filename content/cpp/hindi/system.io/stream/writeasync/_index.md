---
title: WriteAsync()
second_title: Aspose.Slides for C++ API संदर्भ
description: असिंक्रोनस रूप से बाइट्स के अनुक्रम को वर्तमान स्ट्रीम में लिखता है, लिखे गए बाइट्स की संख्या के आधार पर इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।
type: docs
weight: 66
url: /hi/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) विधि


वर्तमान स्ट्रीम में बाइट्स की एक अनुक्रम लिखता है असिंक्रोनस रूप से, लिखे गए बाइट्स की संख्या के आधार पर इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली ऐरे। |
| offset | **int32_t** | **buffer** में उप-रेंज जहाँ से लिखना शुरू होता है, उसका 0-आधारित इंडेक्स। |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या। |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्द करने के अनुरोधों की निगरानी के लिए टोकन। |

### रिटर्न वैल्यू

एक टास्क जो असिंक्रोनस लिखने के ऑपरेशन का प्रतिनिधित्व करता है।

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) विधि


वर्तमान स्ट्रीम में बाइट्स की एक अनुक्रम लिखता है असिंक्रोनस रूप से, लिखे गए बाइट्स की संख्या के आधार पर इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली ऐरे। |
| offset | **int32_t** | **buffer** में उप-रेंज जहाँ से लिखना शुरू होता है, उसका 0-आधारित इंडेक्स। |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या। |

### रिटर्न वैल्यू

एक टास्क जो असिंक्रोनस लिखने के ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [Stream](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)