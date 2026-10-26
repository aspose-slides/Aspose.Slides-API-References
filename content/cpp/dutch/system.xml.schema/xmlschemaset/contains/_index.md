---
title: Contains()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan of een XML Schema definitietaal (XSD) schema met de opgegeven target namespace-URI zich bevindt in de XmlSchemaSet.
type: docs
weight: 196
url: /nl/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) methode

Geeft aan of een XML [Schema](../../) definitietaal (XSD) schema met de opgegeven target namespace-URI zich bevindt in de [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | De **targetNamespace**-eigenschap van het schema. |

### Retourwaarde

**true** als een schema met de opgegeven target namespace-URI zich bevindt in de [XmlSchemaSet](../); anders **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) methode

Geeft aan of het opgegeven XML [Schema](../../) definitietaal (XSD) [XmlSchema](../../xmlschema/)-object zich bevindt in de [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Het [XmlSchema](../../xmlschema/)-object. |

### Retourwaarde

**true** als het [XmlSchema](../../xmlschema/)-object zich bevindt in de [XmlSchemaSet](../); anders **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaSet](../)
* Klasse [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)