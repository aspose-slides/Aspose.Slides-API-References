---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlNodeList containing a list of all descendant elements that match the specified name.
type: docs
weight: 443
url: /system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified name.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name to match. It is matched against the **get_Name** value of the matching node. The special value **\"*\"** matches all tags. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match **name**, the returned collection will be empty.

## XmlDocument::GetElementsByTagName(String, String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlDocument::get_LocalName](../get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The LocalName to match. The special value **\"*\"** matches all tags. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI to match. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match the specified **localName** and **namespaceURI**, the returned collection will be empty.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)