---
title: get_OldValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den ursprünglichen Wert des Knotens zurück.
type: docs
weight: 53
url: /de/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() Methode


Gibt den ursprünglichen Wert des Knotens zurück.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Rückgabewert

Der ursprüngliche Wert des Knotens. Diese Methode gibt **nullptr** zurück, wenn der Knoten weder ein Attribut noch ein Textknoten ist oder wenn der Knoten eingefügt wird. Wird sie in einem **XmlDocument::NodeChanging** Ereignis aufgerufen, gibt **get_OldValue** den aktuellen Wert des Knotens zurück, der ersetzt wird, wenn die Änderung erfolgreich ist. Wird sie in einem **XmlDocument::NodeChanged** Ereignis aufgerufen, gibt **get_OldValue** den Wert des Knotens vor der Änderung zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)