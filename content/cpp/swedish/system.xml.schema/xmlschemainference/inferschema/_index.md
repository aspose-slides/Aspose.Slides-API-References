---
title: InferSchema()
second_title: Aspose.Slides för C++ API-referens
description: Härleder ett XML Schema Definition Language (XSD)-schema från XML-dokumentet som finns i det angivna XmlReader-objektet.
type: docs
weight: 66
url: /sv/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) metod


Härleder ett XML [Schema](../../) definitionsspråk (XSD)-schema från XML-dokumentet som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XML-dokumentet som ett schema ska härledas från. |

### Returvärde

Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller de härledda schemana.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) metod


Härleder ett XML [Schema](../../) definitionsspråk (XSD)-schema från XML-dokumentet som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet och förfinar det härledda schemat med ett befintligt schema i det angivna [XmlSchemaSet](../../xmlschemaset/)-objektet med samma mål-namnrymd.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XML-dokumentet som ett schema ska härledas från. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller ett befintligt schema som används för att förfina det härledda schemat. |

### Returvärde

Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller de härledda schemana.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchemaSet](../../xmlschemaset/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [XmlSchemaInference](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)