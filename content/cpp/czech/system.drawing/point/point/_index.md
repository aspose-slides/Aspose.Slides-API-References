---
title: Point()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový objekt Point a inicializuje hodnoty souřadnic X a Y na 0.
type: docs
weight: 1
url: /cs/system.drawing/point/point/
---
## Point::Point() konstruktor

Vytvoří nový [Point](../) objekt a inicializuje jeho hodnoty souřadnic X a Y na 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) konstruktor

Vytvoří nový [Point](../) objekt a inicializuje jej se zadanými hodnotami.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | int | Hodnota souřadnice X |
| y | int | Hodnota souřadnice Y |

## Point::Point(const Size\&) konstruktor

Vytvoří nový [Point](../) objekt a inicializuje jeho hodnoty souřadnic X a Y hodnotami width a height objektu [SizeF](../../sizef/) odpovídajícím způsobem.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Objekt [SizeF](../../sizef/), jehož hodnoty width a height jsou použity k inicializaci hodnot souřadnic X a Y objektu [Point](../) vytvářeného |

## Point::Point(int) konstruktor

Vytvoří nový [Point](../) objekt a inicializuje hodnotu souřadnice X hodnotou vytvořenou z vyšších 16 bitů zadaného 32-bitového celého čísla a hodnotu souřadnice Y hodnotou vytvořenou z nižších 16 bitů zadaného 32-bitového celého čísla.

```cpp
System::Drawing::Point::Point(int dw)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| dw | int | 32-bitová celá hodnota, jejíž vyšší 16 bitů určuje hodnotu souřadnice X a nížší 16 bitů určuje hodnotu souřadnice Y objektu, který je vytvářen |

## Viz také

* Třída [Point](../)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)