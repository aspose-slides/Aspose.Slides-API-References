---
title: Contains()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda se zadaný bod nachází uvnitř obdélníku reprezentovaného aktuálním objektem.
type: docs
weight: 248
url: /cs/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const metoda

Určuje, zda se zadaný bod nachází uvnitř obdélníku reprezentovaného aktuálním objektem.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | int | X souřadnice bodu k ověření |
| y | int | Y souřadnice bodu k ověření |

### Návratová hodnota

True pokud je určený bod umístěn v obdélníku reprezentovaném aktuálním objektem, jinak - false

## Rectangle::Contains(const Point\&) const metoda

Určuje, zda se zadaný bod nachází uvnitř obdélníku reprezentovaného aktuálním objektem.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Bod k ověření |

### Návratová hodnota

True pokud je určený bod umístěn v obdélníku reprezentovaném aktuálním objektem, jinak - false

## Rectangle::Contains(const Rectangle\&) const metoda

Určuje, zda se zadaný obdélník nachází uvnitř obdélníku reprezentovaného aktuálním objektem.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Obdélník k ověření |

### Návratová hodnota

True pokud je určený obdélník umístěn v obdélníku reprezentovaném aktuálním objektem, jinak - false

## Viz také

* Třída [Rectangle](../)
* Třída [Point](../../point/)
* Obor názvů [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)