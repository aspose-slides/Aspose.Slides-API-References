---
title: GetTile()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy csempe képet a minta kitöltéséhez megadott színekkel.
type: docs
weight: 53
url: /hu/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method


Létrehoz egy csempe képet a minta kitöltéséhez megadott színekkel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | A minta háttér [System::Drawing::Color](../../../system.drawing/color/). |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | A minta előtér [System::Drawing::Color](../../../system.drawing/color/). |

### Visszatérési érték

Csempe [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) method


Létrehoz egy csempe képet a minta kitöltéséhez.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Az alapértelmezett [System::Drawing::Color](../../../system.drawing/color/), amely a ShapeEx StyleEx objektumban van definiálva. A kitöltés színei ettől függhetnek. |

### Visszatérési érték

Csempe [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [IPatternFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)