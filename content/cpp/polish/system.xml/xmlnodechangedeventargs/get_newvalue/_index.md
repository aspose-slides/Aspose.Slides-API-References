---
title: get_NewValue()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca nową wartość węzła.
type: docs
weight: 66
url: /pl/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() metoda

Zwraca nową wartość węzła.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Wartość zwracana

Nowa wartość węzła. Ta metoda zwraca **nullptr**, jeśli węzeł nie jest ani atrybutem, ani węzłem tekstowym, lub jeśli węzeł jest usuwany. Jeśli wywołano w zdarzeniu **XmlDocument::NodeChanging**, **get_NewValue** zwraca wartość węzła, jeśli zmiana zakończy się pomyślnie. Jeśli wywołano w zdarzeniu **XmlDocument::NodeChanged**, **get_NewValue** zwraca bieżącą wartość węzła.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeChangedEventArgs](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)