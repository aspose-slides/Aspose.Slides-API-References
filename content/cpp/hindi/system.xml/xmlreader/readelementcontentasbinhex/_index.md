---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: तत्व को पढ़ता है और BinHex सामग्री को डिकोड करता है।
type: docs
weight: 794
url: /hi/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

तत्व को पढ़ता है और **BinHex** सामग्री को डिकोड करता है।

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें उत्पन्न पाठ की कॉपी की जाएगी। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की कॉपी शुरू करनी है। |
| count | **int32_t** | बफ़र में कॉपी करने के लिये अधिकतम बाइट्स की संख्या। वास्तविक कॉपी की गई बाइट्स की संख्या इस मेथड से रिटर्न होती है। |

### रिटर्न मान

बफ़र में लिखी गई बाइट्स की संख्या।

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)