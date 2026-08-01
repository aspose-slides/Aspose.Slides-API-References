---
title: InferSchema()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent een XML Schema Definition Language (XSD) schema uit het XML-document dat zich bevindt in het opgegeven XmlReader-object.
type: docs
weight: 66
url: /nl/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) methode

Berekent een XML [Schema](../../) Definition Language (XSD) schema uit het XML-document dat zich bevindt in het gespecificeerde [XmlReader](../../../system.xml/xmlreader/)-object.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/)-object dat het XML-document bevat waaruit een schema moet worden afgeleid. |

### Retourwaarde

Een [XmlSchemaSet](../../xmlschemaset/)-object dat de afgeleide schema's bevat.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) methode

Berekent een XML [Schema](../../) Definition Language (XSD) schema uit het XML-document dat zich bevindt in het gespecificeerde [XmlReader](../../../system.xml/xmlreader/)-object, en verfijnt het afgeleide schema met behulp van een bestaand schema in het gespecificeerde [XmlSchemaSet](../../xmlschemaset/)-object met dezelfde doel-namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/)-object dat het XML-document bevat waaruit een schema moet worden afgeleid. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Een [XmlSchemaSet](../../xmlschemaset/)-object dat een bestaand schema bevat dat wordt gebruikt om het afgeleide schema te verfijnen. |

### Retourwaarde

Een [XmlSchemaSet](../../xmlschemaset/)-object dat de afgeleide schema's bevat.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaSet](../../xmlschemaset/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XmlSchemaInference](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)