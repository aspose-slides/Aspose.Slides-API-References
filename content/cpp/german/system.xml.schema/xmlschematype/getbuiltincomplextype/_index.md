---
title: GetBuiltInComplexType()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen XmlSchemaComplexType zurück, der den eingebauten komplexen Typ des angegebenen komplexen Typs darstellt.
type: docs
weight: 196
url: /de/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) Methode

Gibt ein [XmlSchemaComplexType](../../xmlschemacomplextype/) zurück, das den eingebauten komplexen Typ des angegebenen komplexen Typs darstellt.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Einer der XmlTypeCode-Werte, der den komplexen Typ darstellt. |

### Rückgabewert

Das [XmlSchemaComplexType](../../xmlschemacomplextype/), das den eingebauten komplexen Typ darstellt.

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) Methode

Gibt ein [XmlSchemaComplexType](../../xmlschemacomplextype/) zurück, das den eingebauten komplexen Typ des durch qualifizierten Namen angegebenen komplexen Typs darstellt.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Der [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) des komplexen Typs. |

### Rückgabewert

Das [XmlSchemaComplexType](../../xmlschemacomplextype/), das den eingebauten komplexen Typ darstellt.

## Siehe auch

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Klasse [XmlSchemaType](../)
* Klasse [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Namensraum [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)