---
title: ReadContentAsBinHex()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामग्री को पढ़ता है और BinHex डिकोड किए गए बाइनरी बाइट्स को लौटाता है।
type: docs
weight: 781
url: /hi/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

सामग्री को पढ़ता है और **BinHex** डिकोड किए गए बाइनरी बाइट्स को लौटाता है।

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामी पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की कॉपी शुरू की जाएगी। |
| count | **int32_t** | बफ़र में कॉपी किए जाने वाले बाइट्स की अधिकतम संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस मेथड से लौटाई जाती है। |

### रिटर्न वैल्यू

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)