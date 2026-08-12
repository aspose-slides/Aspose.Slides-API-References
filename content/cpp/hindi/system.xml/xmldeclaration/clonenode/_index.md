---
title: CloneNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस नोड की एक प्रतिलिपि बनाता है।
type: docs
weight: 157
url: /hi/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) मेथड

इस नोड की एक प्रतिलिपि बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** निर्दिष्ट नोड के अंतर्गत सबट्री को पुनरावर्ती रूप से क्लोन करने के लिये; **false** केवल नोड को ही क्लोन करने के लिये। क्योंकि [XmlDeclaration](../) नोड्स के बच्चों नहीं होते, क्लोन किया गया नोड हमेशा डेटा मान शामिल करता है, पैरामीटर सेटिंग की परवाह किए बिना। |

### रिटर्न वैल्यू

क्लोन किया गया नोड।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlDeclaration](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)