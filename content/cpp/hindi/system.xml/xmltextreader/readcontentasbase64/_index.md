---
title: ReadContentAsBase64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामग्री को पढ़ता है और Base64 डिकोड किए गए बाइनरी बाइट्स लौटाता है।
type: docs
weight: 638
url: /hi/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

सामग्री को पढ़ता है और **Base64** डिकोड किए गए बाइनरी बाइट्स लौटाता है।

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामी पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम को कॉपी करना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस मेथड से लौटाई जाती है। |

### वापसी मान

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlTextReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)