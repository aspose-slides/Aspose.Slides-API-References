---
title: ReadSubtree()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक नया XmlReader इंस्टेंस लौटाता है जिसका उपयोग वर्तमान नोड और उसकी सभी संतति को पढ़ने के लिए किया जा सकता है।
type: docs
weight: 963
url: /hi/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() विधि

Returns a new [XmlReader](../) instance that can be used to read the current node, and all its descendants.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### रिटर्न वैल्यू

A new XML reader instance set to [ReadState::Initial](../../readstate/). Calling the [XmlReader::Read](../read/) method positions the new reader on the node that was current before the call to the [XmlReader::ReadSubtree](./) method.

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)