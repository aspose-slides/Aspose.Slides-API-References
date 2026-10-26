---
title: Contains()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt of het opgegeven punt zich binnen de rechthoek bevindt die door het huidige object wordt vertegenwoordigd.
type: docs
weight: 248
url: /nl/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const methode


Bepaalt of het opgegeven punt zich binnen het rechthoekige gebied bevindt dat door het huidige object wordt vertegenwoordigd.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | Het X-coördinaat van het te controleren punt |
| y | int | Het Y-coördinaat van het te controleren punt |

### Retourwaarde

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Point\&) const methode


Bepaalt of het opgegeven punt zich binnen het rechthoekige gebied bevindt dat door het huidige object wordt vertegenwoordigd.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Een punt om te controleren |

### Retourwaarde

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Rectangle\&) const methode


Bepaalt of de opgegeven rechthoek zich binnen het rechthoekige gebied bevindt dat door het huidige object wordt vertegenwoordigd.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Een rechthoek om te controleren |

### Retourwaarde

True if the specified rectangle is located within the rectangle represented by the current object, otherwise - false

## Zie ook

* Klasse [Rectangle](../)
* Klasse [Point](../../point/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)