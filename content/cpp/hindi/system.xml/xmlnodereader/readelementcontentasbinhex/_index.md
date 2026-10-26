---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एलिमेंट को पढ़ता है और BinHex सामग्री को डिकोड करता है।
type: docs
weight: 482
url: /hi/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

एलिमेंट को पढ़ता है और BinHex सामग्री को डिकोड करता है।

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामी टेक्स्ट कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम कॉपी करना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस मेथड से वापस मिलती है। |

### वापसी मान

बफ़र में लिखे गए बाइट्स की संख्या।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlNodeReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)