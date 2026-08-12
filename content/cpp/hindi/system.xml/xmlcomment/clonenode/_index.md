---
title: CloneNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस नोड की एक प्रति बनाता है।
type: docs
weight: 40
url: /hi/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) विधि

इस नोड की एक डुप्लिकेट बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### आर्ग्युमेंट्स

| पैरामिटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** को निर्दिष्ट नोड के तहत उप-ट्री को पुनरावर्ती रूप से क्लोन करने के लिए; **false** केवल नोड को ही क्लोन करने के लिए। क्योंकि टिप्पणी नोड्स के पास बच्चे नहीं होते, क्लोन किया गया नोड हमेशा पाठ सामग्री शामिल करता है, पैरामीटर सेटिंग की परवाह किए बिना। |

### वापसी मान

क्लोन किया गया नोड।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlComment](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)