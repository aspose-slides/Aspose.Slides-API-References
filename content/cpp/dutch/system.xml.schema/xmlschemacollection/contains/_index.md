---
title: Contains()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een waarde die aangeeft of de targetNamespace van de gespecificeerde XmlSchema zich in de collectie bevindt.
type: docs
weight: 66
url: /nl/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) methode

Retourneert een waarde die aangeeft of de **targetNamespace** van de gespecificeerde [XmlSchema](../../xmlschema/) zich in de collectie bevindt.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Het [XmlSchema](../../xmlschema/) object. |

### Retourwaarde

**true** als er een schema in de collectie is met dezelfde **targetNamespace**; anders, **false**.

## XmlSchemaCollection::Contains(const String\&) methode

Retourneert een waarde die aangeeft of een schema met de opgegeven namespace zich in de collectie bevindt.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het schema is gekoppeld. Voor XML-schemas is dit doorgaans de target namespace. |

### Retourwaarde

**true** als een schema met de opgegeven namespace zich in de collectie bevindt; anders, **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaCollection](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)