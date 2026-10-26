---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen XmlSchemaSimpleType zurück, der den integrierten einfachen Typ des einfachen Typs darstellt, der durch den qualifizierten Namen angegeben ist.
type: docs
weight: 183
url: /de/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) Methode

Gibt ein [XmlSchemaSimpleType](../../xmlschemasimpletype/) zurück, das den integrierten einfachen Typ des einfachen Typs darstellt, der durch den qualifizierten Namen angegeben ist.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Der [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) des einfachen Typs. |

### Rückgabewert

Das [XmlSchemaSimpleType](../../xmlschemasimpletype/), das den integrierten einfachen Typ darstellt.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) Methode

Gibt ein [XmlSchemaSimpleType](../../xmlschemasimpletype/) zurück, das den integrierten einfachen Typ des angegebenen einfachen Typs darstellt.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Einer der XmlTypeCode-Werte, der den einfachen Typ darstellt. |

### Rückgabewert

Das [XmlSchemaSimpleType](../../xmlschemasimpletype/), das den integrierten einfachen Typ darstellt.

## Siehe auch

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Klasse [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Klasse [XmlSchemaType](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)