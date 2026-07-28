---
title: ReadSubtree()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca nową instancję XmlReader, którą można użyć do odczytania bieżącego węzła oraz wszystkich jego potomków.
type: docs
weight: 963
url: /pl/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metoda

Zwraca nową instancję [XmlReader](../), którą można użyć do odczytania bieżącego węzła i wszystkich jego potomków.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Wartość zwracana

Nowa instancja czytnika XML ustawiona na [ReadState::Initial](../../readstate/). Wywołanie metody [XmlReader::Read](../read/) pozycjonuje nowy czytnik na węzeł, który był bieżący przed wywołaniem metody [XmlReader::ReadSubtree](./).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)