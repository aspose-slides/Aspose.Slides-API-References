---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het XML-schema-definitietaal (XSD) schema toe op de opgegeven URL aan de XmlSchemaSet.
type: docs
weight: 157
url: /nl/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) methode


Voegt het XML [Schema](../../) definitietaal (XSD) schema toe op de opgegeven URL aan de [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | De **targetNamespace**-waarde van het schema, of **nullptr** om de in het schema opgegeven **targetNamespace** te gebruiken. |
| schemaUri | const [String](../../../system/string/)\& | De URL die het te laden schema aangeeft. |

### Retourwaarde

Een [XmlSchema](../../xmlschema/) object als het schema geldig is. Als het schema niet geldig is en een ValidationEventHandler is opgegeven, wordt **nullptr** geretourneerd en wordt het passende validatie-event opgehaald. Anders wordt een XmlSchemaException gegooid.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) methode


Voegt het XML [Schema](../../) definitietaal (XSD) schema dat zich bevindt in de [XmlReader](../../../system.xml/xmlreader/) toe aan de [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | De **targetNamespace**-waarde van het schema, of **nullptr** om de in het schema opgegeven **targetNamespace** te gebruiken. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Het [XmlReader](../../../system.xml/xmlreader/) object. |

### Retourwaarde

Een [XmlSchema](../../xmlschema/) object als het schema geldig is. Als het schema niet geldig is en een ValidationEventHandler is opgegeven, wordt **nullptr** geretourneerd en wordt het passende validatie-event opgehaald. Anders wordt een XmlSchemaException gegooid.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) methode


Voegt alle XML [Schema](../../) definitietaal (XSD) schema’s in de opgegeven [XmlSchemaSet](../) toe aan de [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Het [XmlSchemaSet](../) object. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) methode


Voegt de opgegeven [XmlSchema](../../xmlschema/) toe aan de [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Het [XmlSchema](../../xmlschema/) object dat moet worden toegevoegd aan de [XmlSchemaSet](../). |

### Retourwaarde

Een [XmlSchema](../../xmlschema/) object als het schema geldig is. Als het schema niet geldig is en een ValidationEventHandler is opgegeven, wordt **nullptr** geretourneerd en wordt het passende validatie-event opgehaald. Anders wordt een XmlSchemaException gegooid.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaSet](../)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)