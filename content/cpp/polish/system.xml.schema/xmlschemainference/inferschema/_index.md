---
title: InferSchema()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Inferuje schemat XML Schema Definition Language (XSD) z dokumentu XML zawartego w określonym obiekcie XmlReader.
type: docs
weight: 66
url: /pl/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) metoda

Inferuje schemat XML [Schema](../../) Definition Language (XSD) z dokumentu XML zawartego w określonym obiekcie [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający dokument XML, z którego ma być inferowany schemat. |

### Wartość zwracana

Obiekt [XmlSchemaSet](../../xmlschemaset/) zawierający inferowane schematy.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) metoda

Inferuje schemat XML [Schema](../../) Definition Language (XSD) z dokumentu XML zawartego w określonym obiekcie [XmlReader](../../../system.xml/xmlreader/), i udoskonala wygenerowany schemat przy użyciu istniejącego schematu w określonym obiekcie [XmlSchemaSet](../../xmlschemaset/) o tym samym docelowym namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający dokument XML, z którego ma być inferowany schemat. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Obiekt [XmlSchemaSet](../../xmlschemaset/) zawierający istniejący schemat używany do udoskonalenia inferowanego schematu. |

### Wartość zwracana

Obiekt [XmlSchemaSet](../../xmlschemaset/) zawierający inferowane schematy.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchemaSet](../../xmlschemaset/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [XmlSchemaInference](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)