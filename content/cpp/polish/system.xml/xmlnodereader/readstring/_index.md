---
title: ReadString()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Odczytuje zawartość elementu lub węzła tekstowego jako ciąg znaków.
type: docs
weight: 391
url: /pl/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() metoda


Odczytuje zawartość elementu lub węzła tekstowego jako ciąg znaków.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### Wartość zwracana

Zawartość elementu lub węzła podobnego do tekstowego (Może zawierać CDATA, [Text](../../../system.text/) węzły i tak dalej). Może to być pusty ciąg, jeśli czytnik jest ustawiony na coś innego niż element lub węzeł tekstowy, lub jeśli nie ma już więcej treści tekstowej do zwrócenia w bieżącym kontekście. Uwaga: węzeł tekstowy może być zarówno elementem, jak i węzłem tekstowym atrybutu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)