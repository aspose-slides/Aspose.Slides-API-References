---
title: get_NewValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den neuen Wert des Knotens zurück.
type: docs
weight: 66
url: /de/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() Methode

Gibt den neuen Wert des Knotens zurück.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Rückgabewert

Der neue Wert des Knotens. Diese Methode gibt **nullptr** zurück, wenn der Knoten weder ein Attribut noch ein Textknoten ist oder wenn der Knoten entfernt wird. Wird sie in einem **XmlDocument::NodeChanging**-Ereignis aufgerufen, gibt **get_NewValue** den Wert des Knotens zurück, wenn die Änderung erfolgreich ist. Wird sie in einem **XmlDocument::NodeChanged**-Ereignis aufgerufen, gibt **get_NewValue** den aktuellen Wert des Knotens zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)