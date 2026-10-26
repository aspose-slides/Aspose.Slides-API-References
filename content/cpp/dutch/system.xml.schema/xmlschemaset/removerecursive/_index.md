---
title: RemoveRecursive()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het opgegeven XML-schema definitietaal (XSD) schema en alle schema's die het importeert uit de XmlSchemaSet.
type: docs
weight: 183
url: /nl/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) methode

Verwijdert het opgegeven XML [Schema](../../) definitietaal (XSD) schema en alle schema's die het importeert van de [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Het [XmlSchema](../../xmlschema/) object om te verwijderen uit de [XmlSchemaSet](../). |

### Retourwaarde

**true** als het [XmlSchema](../../xmlschema/) object en al zijn imports succesvol zijn verwijderd; anders, **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaSet](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)