---
title: GetTile()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.
type: docs
weight: 53
url: /nl/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) methode

Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | De achtergrond [System::Drawing::Color](../../../system.drawing/color/) voor het patroon. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | De voorgrond [System::Drawing::Color](../../../system.drawing/color/) voor het patroon. |

### Retourwaarde

Tegel [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) methode

Maakt een tegelafbeelding voor de patroonvulling.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | De standaard [System::Drawing::Color](../../../system.drawing/color/) |

### Retourwaarde

Tegel [IImage](../../iimage/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [PatternFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)