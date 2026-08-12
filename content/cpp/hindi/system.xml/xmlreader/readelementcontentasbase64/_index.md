---
title: ReadElementContentAsBase64()
second_title: C++ API रेफ़रेंस के लिए Aspose.Slides
description: तत्व को पढ़ता है और Base64 सामग्री को डिकोड करता है।
type: docs
weight: 768
url: /hi/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

तत्व को पढ़ता है और **Base64** सामग्री को डिकोड करता है।

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | उस बफ़र जहाँ परिणामी पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम की प्रतिलिपि शुरू की जाएगी। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। वास्तविक कॉपी किए गए बाइट्स की संख्या इस मेथड से वापस मिलती है। |

### रिटर्न वैल्यू

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)