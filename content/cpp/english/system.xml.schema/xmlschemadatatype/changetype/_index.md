---
title: ChangeType()
second_title: Aspose.Slides for C++ API Reference
description: Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the XmlSchemaDatatype, to the run-time type specified.
type: docs
weight: 66
url: /system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](../), to the run-time type specified.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The input value to convert to the specified type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | The target type to convert the input value to. |

### Return Value

The converted input value.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Converts the value specified, whose type is one of the valid representations of the XML schema type represented by the [XmlSchemaDatatype](../), to the run-time type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) if the [XmlSchemaDatatype](../) represents the **xs:QName** type or a type derived from it.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The input value to convert to the specified type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | The target type to convert the input value to. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | An [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) used for resolving namespace prefixes. This is only of use if the [XmlSchemaDatatype](../) represents the **xs:QName** type or a type derived from it. |

### Return Value

The converted input value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)