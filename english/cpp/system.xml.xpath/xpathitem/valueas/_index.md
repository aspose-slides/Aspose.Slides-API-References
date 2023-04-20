---
title: ValueAs()
second_title: Aspose.Slides for C++ API Reference
description: Returns the item's value as the specified type.
type: docs
weight: 131
url: /cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Returns the item's value as the specified type.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The type to return the item value as. |

### Return Value

The value of the item as the type requested.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


When overridden in a derived class, returns the item's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The type to return the item's value as. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### Return Value

The value of the item as the type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)