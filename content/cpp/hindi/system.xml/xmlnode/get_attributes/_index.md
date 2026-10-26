---
title: get_Attributes()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वापस देता है एक XmlAttributeCollection जिसमें इस नोड के गुण होते हैं।
type: docs
weight: 105
url: /hi/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() मेथड

वापस देता है एक [XmlAttributeCollection](../../xmlattributecollection/) जिसमें इस नोड के गुण होते हैं।

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```

### रिटर्न वैल्यू

एक [XmlAttributeCollection](../../xmlattributecollection/) जिसमें नोड के गुण होते हैं। यदि नोड का प्रकार [XmlNodeType::Element](../../xmlnodetype/) है, तो नोड के गुण वापस किए जाते हैं। अन्यथा, यह मेथड **nullptr** वापस करता है।

## देखिए

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttributeCollection](../../xmlattributecollection/)
* क्लास [XmlNode](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)