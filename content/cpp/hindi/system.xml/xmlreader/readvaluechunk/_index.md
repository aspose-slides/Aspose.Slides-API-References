---
title: ReadValueChunk()
second_title: Aspose.Slides for C++ API संदर्भ
description: XML दस्तावेज़ में एम्बेडेड बड़े टेक्स्ट स्ट्रीम को पढ़ता है।
type: docs
weight: 807
url: /hi/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) method

XML दस्तावेज़ में एम्बेडेड बड़े टेक्स्ट स्ट्रीम को पढ़ता है।

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | वह अक्षरों का एरे जो बफ़र के रूप में कार्य करता है जिसमें टेक्स्ट सामग्री लिखी जाती है। यह मान **nullptr** नहीं हो सकता। |
| index | **int32_t** | बफ़र के भीतर वह ऑफ़सेट जहाँ [XmlReader](../) परिणामों को कॉपी करना शुरू कर सकता है। |
| count | **int32_t** | बफ़र में कॉपी करने के लिए अधिकतम अक्षरों की संख्या। वास्तविक कॉपी किए गए अक्षरों की संख्या इस विधि से लौटायी जाती है। |

### Return Value

बफ़र में पढ़े गए अक्षरों की संख्या। जब और कोई टेक्स्ट सामग्री नहीं बची होती है तो शून्य मान लौटाया जाता है।

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)