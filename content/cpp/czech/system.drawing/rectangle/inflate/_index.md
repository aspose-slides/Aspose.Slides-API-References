---
title: Inflate()
second_title: Aspose.Slides pro C++ API Reference
description: Zvětšuje šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachovává polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o určené hodnoty.
type: docs
weight: 261
url: /cs/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metoda

Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| width | int | Množství, o které má být šířka obdélníku zvětšena v obou směrech |
| height | int | Množství, o které má být výška obdélníku zvětšena v obou směrech |

## Rectangle::Inflate(const Size\&) metoda

Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o hodnoty šířky a výšky určené příslušnými hodnotami objektu size.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Objekt [Size](../../size/) určující množství, o které má být šířka a výška obdélníku zvětšena |

## Rectangle::Inflate(const Rectangle\&, int, int) metoda

Zvětší šířku a výšku obdélníku reprezentovaného zadaným objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Obdélník k rozšíření |
| x | int | Množství, o které má být šířka obdélníku zvětšena v obou směrech |
| y | int | Množství, o které má být výška obdélníku zvětšena v obou směrech |

### Návratová hodnota

Objekt [Rectangle](../) představující zvětšený obdélník

## Viz také

* Třída [Rectangle](../)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)