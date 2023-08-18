---
title: ValueAs()
second_title: Aspose.Slides for C++ API Reference
description: Returns the current node's value as the Type specified, using the IXmlNamespaceResolver object specified to resolve namespace prefixes.
type: docs
weight: 378
url: /system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Returns the current node's value as the Type specified, using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The Type to return the current node's value as. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### Return Value

The value of the current node as the Type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)