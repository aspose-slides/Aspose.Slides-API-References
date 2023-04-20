---
title: HasAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the current node has an attribute with the specified name.
type: docs
weight: 300
url: /cpp/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) method


Determines whether the current node has an attribute with the specified name.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the attribute to find. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### Return Value

**true** if the current node has the specified attribute; otherwise, **false**.

## XmlElement::HasAttribute(String, String) method


Determines whether the current node has an attribute with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute to find. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute to find. |

### Return Value

**true** if the current node has the specified attribute; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)