---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API संदर्भ
description: तत्व को पढ़ता है और BinHex सामग्री को डिकोड करता है।
type: docs
weight: 677
url: /hi/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) विधि

तत्व को पढ़ता है और **BinHex** सामग्री को डिकोड करता है।

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी टेक्स्ट को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की कॉपी शुरू की जाएगी। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। वास्तव में कॉपी किए गए बाइट्स की संख्या इस मेथड से वापस लौटती है। |

### रिटर्न वैल्यू

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)