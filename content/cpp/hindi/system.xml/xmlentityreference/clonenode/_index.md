---
title: CloneNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस नोड की एक डुप्लिकेट बनाता है।
type: docs
weight: 92
url: /hi/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) method

इस नोड की एक डुप्लिकेट बनाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deep | **bool** | **true** का उपयोग निर्दिष्ट नोड के नीचे के सबट्री को पुनरावर्ती रूप से क्लोन करने के लिए किया जाता है; **false** का उपयोग केवल नोड स्वयं को क्लोन करने के लिए किया जाता है। [XmlEntityReference](../) नोड्स के लिए, यह मेथड हमेशा बिना बच्चों के एक एंटिटी रेफरेंस नोड लौटाता है। प्रतिस्थापन पाठ तब सेट किया जाता है जब नोड को किसी पैरेंट में डाला जाता है। |

## वापसी मान

क्लोन किया गया नोड।

## देखिए

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)