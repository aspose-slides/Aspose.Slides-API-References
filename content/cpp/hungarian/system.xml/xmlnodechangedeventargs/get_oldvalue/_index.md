---
title: get_OldValue()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaadja a csomópont eredeti értékét.
type: docs
weight: 53
url: /hu/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metódus


Visszaadja a csomópont eredeti értékét.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Visszatérési érték

A csomópont eredeti értéke. Ez a metódus **nullptr** értéket ad vissza, ha a csomópont sem attribútum, sem szövegcímke nem, vagy ha a csomópont beszúrásra kerül. Ha egy **XmlDocument::NodeChanging** eseményben hívják, akkor a **get_OldValue** visszaadja a csomópont aktuális értékét, amely a módosítás sikeres esetén lecserélésre kerül. Ha egy **XmlDocument::NodeChanged** eseményben hívják, akkor a **get_OldValue** visszaadja a csomópont módosítás előtti értékét.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeChangedEventArgs](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)