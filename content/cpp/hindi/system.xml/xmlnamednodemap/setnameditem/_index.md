---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API संदर्भ
description: "XmlNode::get_Name मान का उपयोग करके एक XmlNode जोड़ता है."
type: docs
weight: 27
url: /hi/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) विधि

एक [XmlNode](../../xmlnode/) को उसके [XmlNode::get_Name](../../xmlnode/get_name/) मान का उपयोग करके जोड़ता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | एक [XmlNode](../../xmlnode/) जिसे [XmlNamedNodeMap](../) में संग्रहित किया जाता है। यदि उस नाम वाला एक नोड पहले से ही मानचित्र में मौजूद है, तो उसे नए नोड द्वारा प्रतिस्थापित किया जाता है। |

### वापसी मान

यदि **node** समान नाम वाले मौजूदा नोड को प्रतिस्थापित करता है, तो पुराना नोड वापस किया जाता है; अन्यथा, **nullptr** वापस किया जाता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlNamedNodeMap](../)
* नामस्थान [System::Xml](../../)
* Library [Aspose.Slides](../../../)