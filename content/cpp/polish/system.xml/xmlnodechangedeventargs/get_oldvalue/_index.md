---
title: get_OldValue()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca pierwotną wartość węzła.
type: docs
weight: 53
url: /pl/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metoda


Zwraca pierwotną wartość węzła.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Wartość zwracana

Pierwotna wartość węzła. Ta metoda zwraca **nullptr**, jeśli węzeł nie jest ani atrybutem, ani węzłem tekstowym, lub jeśli węzeł jest wstawiany. Jeśli wywołana w zdarzeniu **XmlDocument::NodeChanging**, **get_OldValue** zwraca bieżącą wartość węzła, który zostanie zastąpiony, jeśli zmiana zakończy się powodzeniem. Jeśli wywołana w zdarzeniu **XmlDocument::NodeChanged**, **get_OldValue** zwraca wartość węzła przed zmianą.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeChangedEventArgs](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)