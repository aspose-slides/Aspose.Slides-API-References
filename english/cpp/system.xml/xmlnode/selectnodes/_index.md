---
title: SelectNodes()
second_title: Aspose.Slides for C++ API Reference
description: Selects a list of nodes matching the XPath expression.
type: docs
weight: 365
url: /cpp/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


Selects a list of nodes matching the [XPath](../../../system.xml.xpath/) expression.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) expression. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a collection of nodes matching the [XPath](../../../system.xml.xpath/) query.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selects a list of nodes matching the [XPath](../../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) expression. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | An [XmlNamespaceManager](../../xmlnamespacemanager/) to use for resolving namespaces for prefixes in the [XPath](../../../system.xml.xpath/) expression. |

### Return Value

An [XmlNodeList](../../xmlnodelist/) containing a collection of nodes matching the [XPath](../../../system.xml.xpath/) query.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)