---
title: GetTile()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.
type: docs
weight: 53
url: /de/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) Methode

Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Der Hintergrund [System::Drawing::Color](../../../system.drawing/color/) für das Muster. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Der Vordergrund [System::Drawing::Color](../../../system.drawing/color/) für das Muster. |

### Rückgabewert

Kachel [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) Methode

Erstellt ein Kachelbild für die Musterfüllung.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Der Standard [System::Drawing::Color](../../../system.drawing/color/) |

### Rückgabewert

Kachel [IImage](../../iimage/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [PatternFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)