---
title: CloneNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस नोड की एक प्रतिलिपि बनाता है। एंटिटी नोड को क्लोन नहीं किया जा सकता। इस मेथड को XmlEntity ऑब्जेक्ट पर कॉल करने पर एक अपवाद उत्पन्न होता है।
type: docs
weight: 170
url: /hi/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) मेथड


इस नोड की एक प्रतिलिपि बनाता है। एंटिटी नोड को क्लोन नहीं किया जा सकता। [XmlEntity](../) ऑब्जेक्ट पर इस मेथड को कॉल करने पर एक अपवाद फेंका जाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** को निर्दिष्ट नोड के नीचे सबट्री को पुनरावर्ती रूप से क्लोन करने के लिए; **false** को केवल नोड को स्वयं क्लोन करने के लिए। |

### रिटर्न मान

मेथड को कॉल किए गए [XmlNode](../../xmlnode/) की एक कॉपी।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlEntity](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)