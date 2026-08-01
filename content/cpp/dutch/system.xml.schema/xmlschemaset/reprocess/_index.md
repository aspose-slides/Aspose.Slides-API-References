---
title: Reprocess()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt een XML Schema definitietaal (XSD) schema dat al bestaat in de XmlSchemaSet.
type: docs
weight: 222
url: /nl/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) methode


Verwerkt een XML [Schema](../../) definitietaal (XSD) schema dat al bestaat in de [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Het schema om opnieuw te verwerken. |

### Retourwaarde

Een [XmlSchema](../../xmlschema/) object als het schema een geldig schema is. Als het schema niet geldig is en een ValidationEventHandler is opgegeven, wordt **nullptr** geretourneerd en wordt het juiste validatie-evenement opgehaald. Anders wordt een XmlSchemaException gegooid.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)