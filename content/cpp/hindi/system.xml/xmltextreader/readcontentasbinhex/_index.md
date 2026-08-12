---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: सामग्री को पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है।
type: docs
weight: 664
url: /hi/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड


सामग्री को पढ़ता है और **BinHex** डिकोडेड बाइनरी बाइट्स लौटाता है।

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी टेक्स्ट कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता है। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ से परिणाम कॉपी करना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। वास्तविक कॉपी किए गए बाइट्स की संख्या इस मेथड से लौटाई जाती है। |

### वापसी मान

बफ़र में लिखे गए बाइट्स की संख्या।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)