---
title: get_NewParent()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "ऑपरेशन पूर्ण होने के बाद XmlNode::get_ParentNode का मान लौटाता है।"
type: docs
weight: 40
url: /hi/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() विधि

ऑपरेशन पूर्ण होने के बाद [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) का मान लौटाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### रिटर्न वैल्यू

ऑपरेशन पूर्ण होने के बाद **ParentNode** का मान। यदि नोड हटाया जा रहा है तो यह विधि **nullptr** लौटाती है। एट्रीब्यूट नोड्स के लिए, यह विधि [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) मान लौटा देती है।

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlNodeChangedEventArgs](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)