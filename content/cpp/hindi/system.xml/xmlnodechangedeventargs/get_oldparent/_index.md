---
title: get_OldParent()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऑपरेशन शुरू होने से पहले XmlNode::get_ParentNode का मान लौटाता है।"
type: docs
weight: 27
url: /hi/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() मेथड

ऑपरेशन शुरू होने से पहले [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) का मान लौटाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Return Value

ऑपरेशन शुरू होने से पहले **ParentNode** का मान। यदि नोड का कोई पैरेंट नहीं था तो यह मेथड **nullptr** लौटाता है। एट्रिब्यूट नोड्स के लिए यह मेथड [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) मान लौटाता है।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)