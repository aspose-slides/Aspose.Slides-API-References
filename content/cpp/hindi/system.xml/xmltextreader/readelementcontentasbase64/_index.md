---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: तत्व को पढ़ता है और Base64 सामग्री को डिकोड करता है।
type: docs
weight: 651
url: /hi/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

तत्व को पढ़ता है और Base64 सामग्री को डिकोड करता है।

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र जिसमें परिणामी पाठ को कॉपी किया जाएगा। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र में वह ऑफ़सेट जहाँ परिणाम की प्रतिलिपि बनाना शुरू किया जाएगा। |
| count | **int32_t** | बफ़र में कॉपी किए जाने वाले बाइट्स की अधिकतम संख्या। कॉपी किए गए बाइट्स की वास्तविक संख्या इस मेथड से लौटाई जाती है। |

### Return Value

बफ़र में लिखे गए बाइट्स की संख्या।

## See Also

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)