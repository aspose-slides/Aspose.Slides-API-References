---
title: ReadContentAsBinHex()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: सामग्री को पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है।
type: docs
weight: 599
url: /hi/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

सामग्री को पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है।

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामस्वरूप पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम कॉपी करना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। वास्तविक कॉपी किए गए बाइट्स की संख्या इस मेथड से लौटाई जाती है। |

### वापसी मान

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)