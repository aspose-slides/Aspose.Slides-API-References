---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar det första underordnade elementet med det angivna XmlNode::get_Name."
type: docs
weight: 586
url: /sv/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) method


Returnerar det första underordnade elementet med den angivna [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på elementet som ska hämtas. |

### Return Value

Det första [XmlElement](../../xmlelement/) som matchar det angivna namnet. Den returnerar **nullptr** om ingen matchning finns.

## XmlNode::idx_get(String, String) method


Returnerar det första underordnade elementet med de angivna [XmlNode::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../get_namespaceuri/) värdena.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Det lokala namnet på elementet. |
| ns | [String](../../../system/string/) | Namespace-URI:n för elementet. |

### Return Value

Det första [XmlElement](../../xmlelement/) med matchande **localname** och **ns**. Den returnerar **nullptr** om ingen matchning finns.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)