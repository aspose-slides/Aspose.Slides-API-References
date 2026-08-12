---
title: ReadContentAsBase64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामग्री को पढ़ता है और Base64 डिकोड किए गए बाइनरी बाइट्स लौटाता है।
type: docs
weight: 573
url: /hi/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) विधि

सामग्री को पढ़ता है और Base64 डिकोड किए गए बाइनरी बाइट्स लौटाता है।

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामस्वरूप पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ परिणाम की कॉपी शुरू की जाएगी। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। कॉपी किए गए बाइट्स की वास्तविक संख्या इस विधि से लौटाई जाती है। |

### रिटर्न मान

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)