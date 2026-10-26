---
title: Schemas()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca kolekcję wszystkich schematów języka definicji XML Schema (XSD) w XmlSchemaSet.
type: docs
weight: 248
url: /pl/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() metoda


Zwraca kolekcję wszystkich schematów XML [Schema](../../) definition language (XSD) w [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Wartość zwracana

Obiekt IList zawierający wszystkie schematy, które zostały dodane do [XmlSchemaSet](../). Jeśli do [XmlSchemaSet](../) nie zostały dodane żadne schematy, zwracana jest pusta kolekcja.

## XmlSchemaSet::Schemas(String) metoda


Zwraca kolekcję wszystkich schematów XML [Schema](../../) definition language (XSD) w [XmlSchemaSet](../) należących do podanej przestrzeni nazw.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Właściwość schematu **targetNamespace**. |

### Wartość zwracana

Obiekt IList zawierający wszystkie schematy, które zostały dodane do [XmlSchemaSet](../) i należą do podanej przestrzeni nazw. Jeśli do [XmlSchemaSet](../) nie zostały dodane żadne schematy, zwracana jest pusta kolekcja.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IList](../../../system.collections.generic/ilist/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [XmlSchemaSet](../)
* Klasa [List](../../../system.collections.generic/list/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)