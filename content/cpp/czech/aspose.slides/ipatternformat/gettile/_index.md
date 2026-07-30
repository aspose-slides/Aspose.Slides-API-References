---
title: GetTile()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří obrázek dlaždice pro výplň vzoru s určenými barvami.
type: docs
weight: 53
url: /cs/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metoda

Vytvoří obrázek dlaždice pro výplň vzoru s určenými barvami.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Pozadí [System::Drawing::Color](../../../system.drawing/color/) pro vzor. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Popředí [System::Drawing::Color](../../../system.drawing/color/) pro vzor. |

### Návratová hodnota

Dlaždice [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) metoda

Vytvoří obrázek dlaždice pro výplň vzoru.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Výchozí [System::Drawing::Color](../../../system.drawing/color/), definovaný v objektu StyleEx třídy ShapeEx. Barvy výplně mohou záviset na tomto. |

### Návratová hodnota

Dlaždice [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [Color](../../../system.drawing/color/)
* Třída [IPatternFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)