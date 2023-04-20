---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API Reference
description: "Returns an XmlNodeList containing a list of all descendant elements that match the specified XmlElement::get_Name."
type: docs
weight: 287
url: /cpp/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name tag to match. This is a qualified name. It is matched against the **get_Name** value of the matching node. The asterisk (*) is a special value that matches all tags. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## XmlElement::GetElementsByTagName(String, String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_LocalName](../get_localname/) and [XmlElement::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name to match. The asterisk (*) is a special value that matches all tags. |
| namespaceURI | [String](../../../system/string/) | The namespace URI to match. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)