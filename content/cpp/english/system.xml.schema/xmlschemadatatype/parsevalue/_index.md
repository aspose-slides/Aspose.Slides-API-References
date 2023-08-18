---
title: ParseValue()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, validates the string specified against a built-in or user-defined simple type.
type: docs
weight: 53
url: /system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) method


When overridden in a derived class, validates the **string** specified against a built-in or user-defined simple type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | [String](../../../system/string/) | The **string** to validate against the simple type. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | The [XmlNameTable](../../../system.xml/xmlnametable/) to use for atomization while parsing the **string** if this [XmlSchemaDatatype](../) object represents the **xs:NCName** type. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object to use while parsing the **string** if this [XmlSchemaDatatype](../) object represents the **xs:QName** type. |

### Return Value

An [Object](../../../system/object/) that can be cast safely to the type returned by the [XmlSchemaDatatype::get_ValueType](../get_valuetype/) call.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)