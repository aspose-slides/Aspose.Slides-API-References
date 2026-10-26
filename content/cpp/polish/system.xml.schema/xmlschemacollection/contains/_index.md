---
title: Contains()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zwraca wartość wskazującą, czy targetNamespace określonego XmlSchema znajduje się w kolekcji.
type: docs
weight: 66
url: /pl/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) metoda

Zwraca wartość wskazującą, czy **targetNamespace** określonego [XmlSchema](../../xmlschema/) znajduje się w kolekcji.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Obiekt [XmlSchema](../../xmlschema/). |

### Wartość zwracana

**true** jeśli w kolekcji znajduje się schemat o tym samym **targetNamespace**; w przeciwnym razie **false**.

## XmlSchemaCollection::Contains(const String\&) metoda

Zwraca wartość wskazującą, czy w kolekcji znajduje się schemat z określoną przestrzenią nazw.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw powiązany ze schematem. Dla schematów XML będzie to zazwyczaj docelowa przestrzeń nazw. |

### Wartość zwracana

**true** jeśli w kolekcji znajduje się schemat o podanej przestrzeni nazw; w przeciwnym razie **false**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [XmlSchemaCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)