---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca XmlSchemaSimpleType, który reprezentuje wbudowany typ prosty typu prostego określonego przez nazwę kwalifikowaną.
type: docs
weight: 183
url: /pl/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) metoda

Zwraca [XmlSchemaSimpleType](../../xmlschemasimpletype/) reprezentujący wbudowany typ prosty typu prostego określonego przez nazwę kwalifikowaną.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) typu prostego. |

### Wartość zwracana

[XmlSchemaSimpleType](../../xmlschemasimpletype/) reprezentujący wbudowany typ prosty.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) metoda

Zwraca [XmlSchemaSimpleType](../../xmlschemasimpletype/) reprezentujący wbudowany typ prosty określonego typu prostego.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Jedna z wartości XmlTypeCode reprezentująca typ prosty. |

### Wartość zwracana

[XmlSchemaSimpleType](../../xmlschemasimpletype/) reprezentujący wbudowany typ prosty.

## Zobacz także

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Klasa [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Klasa [XmlSchemaType](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)