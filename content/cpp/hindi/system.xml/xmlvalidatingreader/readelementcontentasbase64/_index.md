---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एलिमेंट को पढ़ता है और Base64 सामग्री को डिकोड करता है।
type: docs
weight: 586
url: /hi/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) विधि

एलिमेंट को पढ़ता है और Base64 सामग्री को डिकोड करता है।

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की कॉपी शुरू की जाएगी। |
| count | **int32_t** | बफ़र में कॉपी किए जाने वाले अधिकतम बाइट्स की संख्या। वास्तविक कॉपी किए गए बाइट्स की संख्या इस विधि से लौटाई जाती है। |

### रिटर्न मान

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)