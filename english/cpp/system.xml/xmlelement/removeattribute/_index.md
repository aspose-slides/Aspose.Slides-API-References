---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Removes an attribute by name.
type: docs
weight: 235
url: /cpp/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) method


Removes an attribute by name.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the attribute to remove. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

## XmlElement::RemoveAttribute(String, String) method


Removes an attribute with the specified local name and namespace URI. (If the removed attribute has a default value, it is immediately replaced).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute to remove. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute to remove. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)