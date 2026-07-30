---
title: InferSchema()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří schéma XML Schema Definition Language (XSD) z XML dokumentu obsaženého ve specifikovaném objektu XmlReader.
type: docs
weight: 66
url: /cs/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) metoda

Vytvoří XML [Schema](../../) Definition Language (XSD) schéma z XML dokumentu obsaženého v objektu [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/) obsahující XML dokument, ze kterého se má odvodit schéma. |

### Návratová hodnota

Objekt [XmlSchemaSet](../../xmlschemaset/) obsahující odvozená schémata.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) metoda

Vytvoří XML [Schema](../../) Definition Language (XSD) schéma z XML dokumentu obsaženého v objektu [XmlReader](../../../system.xml/xmlreader/) a upřesní odvozené schéma pomocí existujícího schématu v objektu [XmlSchemaSet](../../xmlschemaset/) se stejným cílovým jmenným prostorem.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/) obsahující XML dokument, ze kterého se má odvodit schéma. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Objekt [XmlSchemaSet](../../xmlschemaset/) obsahující existující schéma použité k upřesnění odvozeného schématu. |

### Návratová hodnota

Objekt [XmlSchemaSet](../../xmlschemaset/) obsahující odvozená schémata.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchemaSet](../../xmlschemaset/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Třída [XmlSchemaInference](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)