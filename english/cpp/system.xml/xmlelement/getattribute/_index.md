---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value for the attribute with the specified name.
type: docs
weight: 209
url: /cpp/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) method


Returns the value for the attribute with the specified name.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the attribute to retrieve. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### Return Value

The value of the specified attribute. An empty string is returned if a matching attribute is not found or if the attribute does not have a specified or default value.

## XmlElement::GetAttribute(String, String) method


Returns the value for the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute to retrieve. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute to retrieve. |

### Return Value

The value of the specified attribute. An empty string is returned if a matching attribute is not found or if the attribute does not have a specified or default value.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)