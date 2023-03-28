---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API Reference
description: Returns the in-scope namespaces of the current node.
type: docs
weight: 430
url: /cpp/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope([XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)) method


Returns the in-scope namespaces of the current node.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) | An XmlNamespaceScope value specifying the namespaces to return. |

### Return Value

An IDictionary collection of namespace names keyed by prefix.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
