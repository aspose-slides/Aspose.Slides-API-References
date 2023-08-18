---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API Reference
description: Selects the first XmlNode that matches the XPath expression.
type: docs
weight: 352
url: /system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method


Selects the first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) expression.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) expression. |

### Return Value

The first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) query or **nullptr** if no matching node is found.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selects the first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) expression. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | An [XmlNamespaceManager](../../xmlnamespacemanager/) to use for resolving namespaces for prefixes in the [XPath](../../../system.xml.xpath/) expression. |

### Return Value

The first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) query or **nullptr** if no matching node is found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)