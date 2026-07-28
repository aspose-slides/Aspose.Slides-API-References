---
title: GetTile()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami.
type: docs
weight: 53
url: /pl/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metoda

Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Tło [System::Drawing::Color](../../../system.drawing/color/) dla wzoru. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Pierwszy plan [System::Drawing::Color](../../../system.drawing/color/) dla wzoru. |

### Wartość zwracana

Kafelek [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) metoda

Tworzy obraz kafelka dla wypełnienia wzorem.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Domyślny [System::Drawing::Color](../../../system.drawing/color/), zdefiniowany w obiekcie StyleEx klasy ShapeEx. Kolory wypełnienia mogą zależeć od tego. |

### Wartość zwracana

Kafelek [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [IPatternFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)