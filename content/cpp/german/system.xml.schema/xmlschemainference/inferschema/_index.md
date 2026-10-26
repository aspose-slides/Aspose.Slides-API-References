---
title: InferSchema()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt ein XML Schema Definition Language (XSD)-Schema aus dem im angegebenen XmlReader-Objekt enthaltenen XML-Dokument.
type: docs
weight: 66
url: /de/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) Methode

Ermittelt ein XML [Schema](../../) Definition Language (XSD)-Schema aus dem im angegebenen [XmlReader](../../../system.xml/xmlreader/)-Objekt enthaltenen XML-Dokument.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/)-Objekt, das das XML-Dokument enthält, aus dem ein Schema ermittelt werden soll. |

### Rückgabewert

Ein [XmlSchemaSet](../../xmlschemaset/)-Objekt, das die ermittelten Schemata enthält.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) Methode

Ermittelt ein XML [Schema](../../) Definition Language (XSD)-Schema aus dem im angegebenen [XmlReader](../../../system.xml/xmlreader/)-Objekt enthaltenen XML-Dokument und verfeinert das ermittelte Schema mithilfe eines vorhandenen Schemas im angegebenen [XmlSchemaSet](../../xmlschemaset/)-Objekt mit demselben Ziel-Namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/)-Objekt, das das XML-Dokument enthält, aus dem ein Schema ermittelt werden soll. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Ein [XmlSchemaSet](../../xmlschemaset/)-Objekt, das ein vorhandenes Schema enthält, das zum Verfeinern des ermittelten Schemas verwendet wird. |

### Rückgabewert

Ein [XmlSchemaSet](../../xmlschemaset/)-Objekt, das die ermittelten Schemata enthält.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchemaSet](../../xmlschemaset/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XmlSchemaInference](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)