---
title: AddNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Adds the given namespace to the collection.
type: docs
weight: 66
url: /cpp/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace([String](../../../system/string/), [String](../../../system/string/)) method


Adds the given namespace to the collection.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The prefix to associate with the namespace being added. Use [String::Empty](../../../system/string/empty/) to add a default namespace. If the [XmlNamespaceManager](../) will be used for resolving namespaces in an XML Path Language ([XPath](../../../system.xml.xpath/)) expression, a prefix must be specified. If an [XPath](../../../system.xml.xpath/) expression does not include a prefix, it is assumed that the namespace Uniform Resource Identifier (URI) is the empty namespace. For more information about [XPath](../../../system.xml.xpath/) expressions and the [XmlNamespaceManager](../), refer to the XmlNode::SelectNodes(String) and XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) methods. |
| uri | [String](../../../system/string/) | The namespace to add. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
