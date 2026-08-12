---
title: CloneNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस नोड की एक प्रति बनाता है। नोटेशन नोड को क्लोन नहीं किया जा सकता। इस मेथड को XmlNotation ऑब्जेक्ट पर कॉल करने पर एक अपवाद फेंका जाता है।
type: docs
weight: 118
url: /hi/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) विधि

Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an [XmlNotation](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** निर्दिष्ट नोड के अंतर्गत उपवृक्ष को पुनरावृति रूप से क्लोन करने के लिए; **false** केवल स्वयं नोड को क्लोन करने के लिए। |

### रिटर्न मान

A [XmlNode](../../xmlnode/) copy of the node from which the method is called.

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlNotation](../)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)