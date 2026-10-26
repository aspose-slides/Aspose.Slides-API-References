---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: घटक को पढ़ता है और Base64 सामग्री को डिकोड करता है।
type: docs
weight: 469
url: /hi/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) मेथड


घटक को पढ़ता है और Base64 सामग्री को डिकोड करता है।

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | वह बफ़र जिसमें परिणामी पाठ को कॉपी किया जाता है। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ परिणाम की प्रतिलिपि शुरू की जानी है। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम बाइट्स की संख्या। वास्तविक कॉपी की गई बाइट्स की संख्या इस मेथड से वापस आती है। |

### Return Value

बफ़र में लिखी गई बाइट्स की संख्या।

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)