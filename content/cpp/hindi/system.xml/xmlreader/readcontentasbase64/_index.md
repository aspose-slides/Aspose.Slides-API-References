---
title: ReadContentAsBase64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामग्री को पढ़ता है और Base64 डिकोडेड द्विआधारी बाइट्स लौटाता है।
type: docs
weight: 755
url: /hi/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड

सामग्री को पढ़ता है और Base64 डिकोडेड द्विआधारी बाइट्स लौटाता है।

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी टेक्स्ट को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम को कॉपी करना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी किए जाने वाले बाइट्स की अधिकतम संख्या। कॉपी किए गए वास्तविक बाइट्स की संख्या इस मेथड से लौटाई जाती है। |

### रिटर्न वैल्यू

बफ़र में लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)