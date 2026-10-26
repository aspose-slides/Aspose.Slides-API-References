---
title: Contains()
second_title: Aspose.Slides dla C++ – Referencja API
description: Wskazuje, czy schemat języka definicyjnego XML Schema (XSD) z określonym docelowym URI przestrzeni nazw znajduje się w XmlSchemaSet.
type: docs
weight: 196
url: /pl/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metoda

Wskazuje, czy schemat języka definicyjnego XML [Schema](../../) (XSD) z określonym docelowym URI przestrzeni nazw znajduje się w [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Właściwość **targetNamespace** schematu. |

### Wartość zwracana

**true** jeśli schemat z określonym docelowym URI przestrzeni nazw znajduje się w [XmlSchemaSet](../); w przeciwnym razie **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metoda

Wskazuje, czy określony obiekt XML [Schema](../../) języka definicyjnego (XSD) [XmlSchema](../../xmlschema/) znajduje się w [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Obiekt [XmlSchema](../../xmlschema/). |

### Wartość zwracana

**true** jeśli obiekt [XmlSchema](../../xmlschema/) znajduje się w [XmlSchemaSet](../); w przeciwnym razie **false**.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaSet](../)
* Klasa [XmlSchema](../../xmlschema/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)