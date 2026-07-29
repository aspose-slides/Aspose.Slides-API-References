---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till XML Schema definitionsspråk (XSD) schema på den angivna URL:en till XmlSchemaSet.
type: docs
weight: 157
url: /sv/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metod

Lägger till XML [Schema](../../) definitionsspråk (XSD) schema på den angivna URL:en till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaUri | const [String](../../../system/string/)\& | The URL that specifies the schema to load. |

### Returvärde

Ett [XmlSchema](../../xmlschema/)-objekt om schemat är giltigt. Om schemat inte är giltigt och en ValidationEventHandler har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metod

Lägger till XML [Schema](../../) definitionsspråk (XSD) schema som finns i [XmlReader](../../../system.xml/xmlreader/) till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object. |

### Returvärde

Ett [XmlSchema](../../xmlschema/)-objekt om schemat är giltigt. Om schemat inte är giltigt och en ValidationEventHandler har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metod

Lägger till alla XML [Schema](../../) definitionsspråk (XSD) scheman i den angivna [XmlSchemaSet](../) till [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | The [XmlSchemaSet](../) object. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metod

Lägger till den angivna [XmlSchema](../../xmlschema/) till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) object to add to the [XmlSchemaSet](../). |

### Returvärde

Ett [XmlSchema](../../xmlschema/)-objekt om schemat är giltigt. Om schemat inte är giltigt och en ValidationEventHandler har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett XmlSchemaException.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)