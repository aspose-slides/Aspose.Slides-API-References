---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API संदर्भ
description: सामग्री को पढ़ता है और Base64 डिकोड किए गये बाइनरी बाइट्स को वापस करता है।
type: docs
weight: 443
url: /hi/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

सामग्री को पढ़ता है और Base64 डीकोड किए गए बाइनरी बाइट्स को वापस करता है।

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामी पाठ कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की कॉपी शुरू होगी। |
| count | **int32_t** | बफ़र में कॉपी किए जाने वाले बाइट्स की अधिकतम संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस मेथड से वापस की जाती है। |

### रिटर्न वैल्यू

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)