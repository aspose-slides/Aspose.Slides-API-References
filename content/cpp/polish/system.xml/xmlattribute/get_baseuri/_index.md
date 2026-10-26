---
title: get_BaseURI()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca podstawowy Uniform Resource Identifier (URI) węzła.
type: docs
weight: 183
url: /pl/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() metoda

Zwraca podstawowy Uniform Resource Identifier (URI) węzła.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### Wartość zwracana

Lokalizacja, z której wczytano węzeł, lub [String::Empty](../../../system/string/empty/) jeśli węzeł nie ma podstawowego URI. [Attribute](../../../system/attribute/) węzły mają taki sam podstawowy URI jak ich element właścicielski. Jeśli węzeł atrybutu nie ma elementu właścicielskiego, get_BaseURI zwraca [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlAttribute](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)