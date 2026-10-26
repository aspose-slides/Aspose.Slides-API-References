---
title: GetTile()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří dlaždicový obrázek pro výplň vzoru se zadanými barvami.
type: docs
weight: 53
url: /cs/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metoda

Vytvoří dlaždicový obrázek pro výplň vzoru se specifikovanými barvami.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Pozadí [System::Drawing::Color](../../../system.drawing/color/) pro vzor. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Popředí [System::Drawing::Color](../../../system.drawing/color/) pro vzor. |

### Návratová hodnota

Tile [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) metoda

Vytvoří dlaždicový obrázek pro výplň vzoru.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Výchozí [System::Drawing::Color](../../../system.drawing/color/) |

### Návratová hodnota

Tile [IImage](../../iimage/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [Color](../../../system.drawing/color/)
* Třída [PatternFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)