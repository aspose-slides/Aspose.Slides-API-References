---
title: GetBuiltInComplexType()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy XmlSchemaComplexType objektumot, amely a megadott komplex típus beépített komplex típusát képviseli.
type: docs
weight: 196
url: /hu/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) metódus

Returns an [XmlSchemaComplexType](../../xmlschemacomplextype/) that represents the built-in complex type of the complex type specified.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | A komplex típust képviselő XmlTypeCode értékek egyike. |

### Visszatérési érték

A [XmlSchemaComplexType](../../xmlschemacomplextype/) amely a beépített komplex típust képviseli.

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) metódus

Returns an [XmlSchemaComplexType](../../xmlschemacomplextype/) that represents the built-in complex type of the complex type specified by qualified name.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | A komplex típus [XmlQualifiedName](../../../system.xml/xmlqualifiedname/). |

### Visszatérési érték

A [XmlSchemaComplexType](../../xmlschemacomplextype/) amely a beépített komplex típust képviseli.

## Lásd még

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Osztály [XmlSchemaType](../)
* Osztály [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)