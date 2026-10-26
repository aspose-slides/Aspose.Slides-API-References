---
title: CloneNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस नोड की एक प्रति बनाता है।
type: docs
weight: 118
url: /hi/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) मेथड

इस नोड की एक प्रति बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** निर्दिष्ट नोड के नीचे के सबट्री को पुनरावर्ती रूप से क्लोन करने के लिए; **false** केवल नोड को ही क्लोन करने के लिए। दस्तावेज़ प्रकार नोड्स के लिए, क्लोन किया गया नोड हमेशा सबट्री को शामिल करता है, पैरामीटर सेटिंग की परवाह किए बिना। |

### वापसी मान

क्लोन किया गया नोड।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)