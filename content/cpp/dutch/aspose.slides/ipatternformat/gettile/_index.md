---
title: GetTile()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.
type: docs
weight: 53
url: /nl/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) methode


Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | De achtergrond [System::Drawing::Color](../../../system.drawing/color/) voor het patroon. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | De voorgrond [System::Drawing::Color](../../../system.drawing/color/) voor het patroon. |

### Retourwaarde

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) methode


Maakt een tegelafbeelding voor de patroonvulling.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | De standaard [System::Drawing::Color](../../../system.drawing/color/), gedefinieerd in het StyleEx-object van ShapeEx. De kleuren van de vulling kunnen hiervan afhankelijk zijn. |

### Retourwaarde

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IPatternFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)