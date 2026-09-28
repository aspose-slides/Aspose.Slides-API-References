---
title: GetTile()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.
type: docs
weight: 53
url: /de/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method


Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Der Hintergrund [System::Drawing::Color](../../../system.drawing/color/) für das Muster. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Der Vordergrund [System::Drawing::Color](../../../system.drawing/color/) für das Muster. |

### Rückgabewert

Tile [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) method


Erstellt ein Kachelbild für die Musterfüllung.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Der Standard-[System::Drawing::Color](../../../system.drawing/color/), definiert im StyleEx-Objekt von ShapeEx. Die Farben der Füllung können davon abhängen. |

### Rückgabewert

Tile [IImage](../../iimage/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IPatternFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)