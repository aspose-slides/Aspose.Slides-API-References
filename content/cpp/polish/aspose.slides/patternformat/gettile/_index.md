---
title: GetTile()
second_title: Aspose.Slides dla C++ - referencja API
description: Tworzy obraz kafelka dla wypełnienia wzorem przy użyciu określonych kolorów.
type: docs
weight: 53
url: /pl/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metoda


Tworzy obraz kafelka dla wypełnienia wzorem o określonych kolorach.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) tła dla wzoru. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) pierwszego planu dla wzoru. |

### Wartość zwracana

Kafelek [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) metoda


Tworzy obraz kafelka dla wypełnienia wzorem.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Domyślny [System::Drawing::Color](../../../system.drawing/color/) |

### Wartość zwracana

Kafelek [IImage](../../iimage/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [PatternFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)