---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API संदर्भ
description: सामग्री को पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है।
type: docs
weight: 456
url: /hi/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) विधि

सामग्री को पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है।

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी पाठ को कॉपी किया जाता है। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम को कॉपी करना शुरू करना है। |
| count | **int32_t** | बफ़र में कॉपी करने के अधिकतम बाइट्स की संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस विधि से लौटाई जाती है। |

### वापसी मान

बफ़र में लिखे गए बाइट्स की संख्या।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)