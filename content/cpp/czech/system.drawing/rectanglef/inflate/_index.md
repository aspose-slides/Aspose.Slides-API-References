---
title: Inflate()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zvětšuje šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachovává polohu geometrického středu obdélníku. Šířka a výška jsou v obou směrech zvětšeny o zadané hodnoty.
type: docs
weight: 261
url: /cs/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) method

Zvětšuje šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachovává polohu geometrického středu obdélníku. Šířka a výška jsou v obou směrech zvětšeny o zadané hodnoty.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| width | **float** | Množství, o které má být šířka obdélníku zvětšena v obou směrech |
| height | **float** | Množství, o které má být výška obdélníku zvětšena v obou směrech |

## RectangleF::Inflate(const SizeF\&) method

Zvětšuje šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachovává polohu geometrického středu obdélníku. Šířka a výška jsou v obou směrech zvětšeny o hodnoty šířky a výšky specifikovaného objektu size odpovídajícím způsobem.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Objekt [SizeF](../../sizef/) určující množství, o které má být šířka a výška obdélníku zvětšena |

## RectangleF::Inflate(const RectangleF\&, float, float) method

Zvětšuje šířku a výšku obdélníku reprezentovaného zadaným objektem, přičemž zachovává polohu geometrického středu obdélníku. Šířka a výška jsou v obou směrech zvětšeny o zadané hodnoty.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Obdélník, který se má zvětšit |
| x | **float** | Množství, o které má být šířka obdélníku zvětšena v obou směrech |
| y | **float** | Množství, o které má být výška obdélníku zvětšena v obou směrech |

### Návratová hodnota

Objekt [RectangleF](../) představující zvětšený obdélník

## Viz také

* Třída [RectangleF](../)
* Třída [SizeF](../../sizef/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)