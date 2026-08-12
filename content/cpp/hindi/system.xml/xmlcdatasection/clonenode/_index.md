---
title: CloneNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस नोड की एक प्रतिलिपि बनाता है।
type: docs
weight: 53
url: /hi/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) method

इस नोड की एक प्रतिलिपि बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** को पुनरावर्ती रूप से निर्दिष्ट नोड के अंतर्गत सबट्री को क्लोन करने के लिए; **false** को केवल नोड को ही क्लोन करने के लिए। क्योंकि CDATA नोड्स के कोई बच्चे नहीं होते, पैरामीटर सेटिंग चाहे जो भी हो, क्लोन किया गया नोड हमेशा डेटा सामग्री शामिल करेगा। |

### वापसी मान

क्लोन किया गया नोड।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)