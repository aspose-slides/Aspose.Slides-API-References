---
title: CloneNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस नोड की एक प्रतिलिपि बनाता है।
type: docs
weight: 79
url: /hi/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) मेथड

इस नोड की एक प्रतिलिपि बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For white space nodes, the cloned node always includes the data value, regardless of the parameter setting. |

### वापसी मान

क्लोन किया गया नोड।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlWhitespace](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)