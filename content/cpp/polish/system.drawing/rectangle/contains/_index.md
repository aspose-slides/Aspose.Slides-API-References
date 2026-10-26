---
title: Contains()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa, czy określony punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt.
type: docs
weight: 248
url: /pl/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const metoda

Określa, czy określony punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | int | Współrzędna X punktu do sprawdzenia |
| y | int | Współrzędna Y punktu do sprawdzenia |

### Wartość zwracana

True, jeśli określony punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt, w przeciwnym razie - false

## Rectangle::Contains(const Point\&) const metoda

Określa, czy określony punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Punkt do sprawdzenia |

### Wartość zwracana

True, jeśli określony punkt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt, w przeciwnym razie - false

## Rectangle::Contains(const Rectangle\&) const metoda

Określa, czy określony prostokąt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Prostokąt do sprawdzenia |

### Wartość zwracana

True, jeśli określony prostokąt znajduje się wewnątrz prostokąta reprezentowanego przez bieżący obiekt, w przeciwnym razie - false

## Zobacz także

* Klasa [Rectangle](../)
* Klasa [Point](../../point/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)