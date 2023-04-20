---
title: ValueAs()
second_title: Aspose.Slides for C++ API Reference
description: Returns the validated XML element or attribute's value as the type specified using the IXmlNamespaceResolver object specified to resolve namespace prefixes.
type: docs
weight: 144
url: /cpp/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Returns the validated XML element or attribute's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The type to return the validated XML element or attribute's value as. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### Return Value

The value of the validated XML element or attribute as the type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)