---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy XmlSchemaSimpleType típusú objektumot, amely a minősített név által megadott egyszerű típus beépített egyszerű típusát képviseli.
type: docs
weight: 183
url: /hu/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) metódus

Visszaad egy [XmlSchemaSimpleType](../../xmlschemasimpletype/) objektumot, amely a minősített név által megadott egyszerű típus beépített egyszerű típusát képviseli.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Az egyszerű típus [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)-ja. |

### Visszatérési érték

A [XmlSchemaSimpleType](../../xmlschemasimpletype/) objektum, amely a beépített egyszerű típust képviseli.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) metódus

Visszaad egy [XmlSchemaSimpleType](../../xmlschemasimpletype/) objektumot, amely a megadott egyszerű típus beépített egyszerű típusát képviseli.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Az egyszerű típust képviselő XmlTypeCode értékek egyike. |

### Visszatérési érték

A [XmlSchemaSimpleType](../../xmlschemasimpletype/) objektum, amely a beépített egyszerű típust képviseli.

## Lásd még

* Enum [XmlTypeCode](../../xmltypecode/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Osztály [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Osztály [XmlSchemaType](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)