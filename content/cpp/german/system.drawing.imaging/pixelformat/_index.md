---
title: PixelFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Farbdatumsformat eines Pixels an.
type: docs
weight: 326
url: /de/system.drawing.imaging/pixelformat/
---
## PixelFormat Aufzählung

Gibt das Farbdatumsformat eines Pixels an.

```cpp
enum class PixelFormat
```

### Werte

| Name | Value | Description |
| --- | --- | --- |
| Indexed | 65536 | Gibt an, dass die Pixeldaten Farbindexwerte enthalten, das heißt, sie sind ein Index zu Farben in der Systemfarbtabelle. |
| Gdi | 131072 | Gibt an, dass die Pixeldaten GDI-Farben enthalten. |
| Alpha | 262144 | Gibt an, dass die Pixeldaten Alphawerte enthalten, die nicht vorgemultipliziert sind. |
| PAlpha | 524288 | Gibt an, dass die Pixeldaten vorgemultiplizierte Alphawerte enthalten. |
| Extended | 1048576 | Reserviert. |
| Canonical | 2097152 | Gibt das Pixelformat von 32 Bit pro Pixel mit 24-Bit Farbtiefe und einem 8-Bit-Alphakanal an. |
| Undefined | 0 | Gibt an, dass das Pixelformat nicht definiert ist. |
| DontCare | 0 | Das Pixelformat ist nicht angegeben. |
| Format1bppIndexed | n/a | Gibt an, dass das Pixelformat 1 Bit pro Pixel indizierte Farbe ist. |
| Format4bppIndexed | n/a | Gibt an, dass das Pixelformat 4 Bit pro Pixel indizierte Farbe ist. |
| Format8bppIndexed | n/a | Gibt an, dass das Pixelformat 8 Bit pro Pixel indizierte Farbe ist. |
| Format16bppGrayScale | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel beträgt. Die Farbinformation spezifiziert 65 536 Graustufen. |
| Format16bppRgb555 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit je 5 Bit für Rot, Grün und Blau enthält und das verbleibende Bit nicht verwendet wird. |
| Format16bppRgb565 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau enthält. |
| Format16bppArgb1555 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit je 5 Bit für Rot, Grün und Blau und 1 Bit für Alpha enthält. |
| Format24bppRgb | n/a | Gibt an, dass das Pixelformat 24 Bit pro Pixel mit je 8 Bit für Rot, Grün und Blau enthält. |
| Format32bppRgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit je 8 Bit für Rot, Grün und Blau und den restlichen 8 Bit nicht verwendet werden. |
| Format32bppArgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit je 8 Bit für Rot, Grün, Blau und Alpha enthält. |
| Format32bppPArgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit je 8 Bit für Rot, Grün, Blau und Alpha enthält. Die Rot-, Grün- und Blau-Komponenten sind gemäß dem Alpha-Wert vorgemultipliziert. |
| Format48bppRgb | n/a | Gibt an, dass das Pixelformat 48 Bit pro Pixel mit je 16 Bit für Rot, Grün und Blau enthält. |
| Format64bppArgb | n/a | Gibt an, dass das Pixelformat 64 Bit pro Pixel mit je 16 Bit für Rot, Grün, Blau und Alpha enthält. |
| Format64bppPArgb | n/a | Gibt an, dass das Pixelformat 64 Bit pro Pixel mit je 16 Bit für Rot, Grün, Blau und Alpha enthält. Die Rot-, Grün- und Blau-Komponenten sind gemäß dem Alpha-Wert vorgemultipliziert. |
| Format32bppCMYK | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit je 8 Bit für Cyan, Magenta, Gelb und Schwarz (Key) enthält. |
| Max | 16 | Der Maximalwert dieser Aufzählung. |

## Siehe auch

* Namensraum [System::Drawing::Imaging](../)
* Bibliothek [Aspose.Slides](../../)