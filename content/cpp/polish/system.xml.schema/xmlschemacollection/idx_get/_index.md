---
title: idx_get()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca XmlSchema powiązany z podanym identyfikatorem URI przestrzeni nazw.
type: docs
weight: 53
url: /pl/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metoda


Zwraca [XmlSchema](../../xmlschema/) powiązany z podanym identyfikatorem URI przestrzeni nazw.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw powiązany ze schematem, który chcesz zwrócić. Zazwyczaj będzie to **targetNamespace** schematu. |

### Wartość zwracana

[XmlSchema](../../xmlschema/) powiązany z identyfikatorem URI przestrzeni nazw; **nullptr** jeśli nie ma wczytanego schematu powiązanego z podaną przestrzenią nazw lub jeśli przestrzeń nazw jest powiązana ze schematem XDR.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlSchema](../../xmlschema/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaCollection](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)