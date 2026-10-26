---
title: GetTile()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehozza a csempe képet a minta kitöltéséhez a megadott színekkel.
type: docs
weight: 53
url: /hu/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metódus


Létrehozza a csempeképet a minta kitöltéséhez megadott színekkel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | A háttér [System::Drawing::Color](../../../system.drawing/color/) a mintához. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Az előtér [System::Drawing::Color](../../../system.drawing/color/) a mintához. |

### Visszatérési érték

Csempe [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) metódus


Létrehozza a csempeképet a minta kitöltéséhez.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Az alapértelmezett [System::Drawing::Color](../../../system.drawing/color/) |

### Visszatérési érték

Csempe [IImage](../../iimage/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [PatternFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)