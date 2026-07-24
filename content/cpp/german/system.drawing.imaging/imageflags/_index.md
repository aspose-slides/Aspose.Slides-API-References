---
title: ImageFlags
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Attribute der von einem Image-Objekt dargestellten Pixeldaten dar.
type: docs
weight: 274
url: /de/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Stellt die Attribute der von einem [Image](../../system.drawing/image/)-Objekt dargestellten Pixeldaten dar.

```cpp
enum class ImageFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Skalierbar. |
| HasAlpha | 2 | Enthält Alphainformationen. |
| HasTranslucent | 4 | Es gibt Alpha-Werte größer als 0 und kleiner als 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Die Pixeldaten werden im RGB-Farbraum dargestellt. |
| ColorSpaceCmyk | 32 | Die Pixeldaten werden im CMYK-Farbraum dargestellt. |
| ColorSpaceGray | 64 | Die Pixeldaten sind in Graustufen. |
| ColorSpaceYcbcr | 128 | Die Pixeldaten werden im YCBCR-Farbraum dargestellt. |
| ColorSpaceYcck | 256 | Die Pixeldaten werden im YCCK-Farbraum dargestellt. |
| HasRealDpi | 4096 | Die DPI-Informationen sind im Bild gespeichert. |
| HasRealPixelSize | 8192 | Die Größe eines Pixels ist im Bild gespeichert. |
| ReadOnly | 65536 | Die Pixeldaten sind schreibgeschützt. |
| Caching | 131072 | Kann für schnelleren Zugriff zwischengespeichert werden. |

## Siehe auch

* Namensraum [System::Drawing::Imaging](../)
* Bibliothek [Aspose.Slides](../../)