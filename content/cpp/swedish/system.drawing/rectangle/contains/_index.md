---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om den angivna punkten är placerad inom rektangeln som representeras av det aktuella objektet.
type: docs
weight: 248
url: /sv/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const metod


Bestämmer om den angivna punkten är placerad inom rektangeln som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska kontrolleras |
| y | int | Y-koordinaten för punkten som ska kontrolleras |

### Returvärde

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Point\&) const metod


Bestämmer om den angivna punkten är placerad inom rektangeln som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [Point](../../point/)\& | En punkt att kontrollera |

### Returvärde

True if the specified point is located within the rectangle represented by the current object, otherwise - false

## Rectangle::Contains(const Rectangle\&) const metod


Bestämmer om den angivna rektangeln är placerad inom rektangeln som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | En rektangel att kontrollera |

### Returvärde

True if the specified rectangle is located within the rectangle represented by the current object, otherwise - false

## Se också

* Klass [Rectangle](../)
* Klass [Point](../../point/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)