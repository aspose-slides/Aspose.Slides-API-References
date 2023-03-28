---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value indicating if the derived schema type specified is derived from the base schema type specified.
type: docs
weight: 209
url: /cpp/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom([SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>, const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\&, [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)) method


Returns a value indicating if the derived schema type specified is derived from the base schema type specified.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | The derived [XmlSchemaType](../) to test. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | The base [XmlSchemaType](../) to test the derived [XmlSchemaType](../) against. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | One of the XmlSchemaDerivationMethod values representing a type derivation method to exclude from testing. |

### Return Value

**true** if the derived type is derived from the base type; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
