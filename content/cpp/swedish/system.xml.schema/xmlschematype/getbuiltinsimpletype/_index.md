---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en XmlSchemaSimpleType som representerar den inbyggda enkla typen för den enkla typen som anges av det kvalificerade namnet.
type: docs
weight: 183
url: /sv/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) metod

Returnerar en [XmlSchemaSimpleType](../../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den enkla typen som anges av det kvalificerade namnet.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Den [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) av den enkla typen. |

### Returvärde

Den [XmlSchemaSimpleType](../../xmlschemasimpletype/) som representerar den inbyggda enkla typen.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) metod

Returnerar en [XmlSchemaSimpleType](../../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den angivna enkla typen.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Ett av XmlTypeCode-värdena som representerar den enkla typen. |

### Returvärde

Den [XmlSchemaSimpleType](../../xmlschemasimpletype/) som representerar den inbyggda enkla typen.

## Se även

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Klass [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Klass [XmlSchemaType](../)
* Namnrymd [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)