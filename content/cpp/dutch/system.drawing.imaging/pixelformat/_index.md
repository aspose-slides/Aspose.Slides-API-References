---
title: PixelFormat
second_title: Aspose.Slides voor C++ API Referentie
description: Specificeert het kleurgegevensformaat van een pixel.
type: docs
weight: 326
url: /nl/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Specificeert het kleurgegevensformaat van een pixel.

```cpp
enum class PixelFormat
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Indexed | 65536 | Specificeert dat de pixelgegevens gekleurde geïndexeerde waarden bevatten, wat betekent dat ze een index zijn naar kleuren in de systeemtabel voor kleuren. |
| Gdi | 131072 | Specificeert dat de pixelgegevens GDI-kleuren bevatten. |
| Alpha | 262144 | Specificeert dat de pixelgegevens alpha-waarden bevatten die niet vooraf vermenigvuldigd zijn. |
| PAlpha | 524288 | Specificeert dat de pixelgegevens vooraf vermenigvuldigde alpha-waarden bevatten. |
| Extended | 1048576 | Gereserveerd. |
| Canonical | 2097152 | Specificeert het pixelformaat van 32 bits per pixel met een kleurdiepte van 24 bits en een 8-bit alpha-kanaal. |
| Undefined | 0 | Specificeert dat het pixelformaat ongedefinieerd is. |
| DontCare | 0 | Het pixelformaat is niet opgegeven. |
| Format1bppIndexed | n/a | Specificeert dat het pixelformaat 1 bit per pixel geïndexeerde kleur is. |
| Format4bppIndexed | n/a | Specificeert dat het pixelformaat 4 bits per pixel geïndexeerde kleur is. |
| Format8bppIndexed | n/a | Specificeert dat het pixelformaat 8 bits per pixel geïndexeerde kleur is. |
| Format16bppGrayScale | n/a | Specificeert dat het pixelformaat 16 bits per pixel is. De kleurinformatie specificeert 65536 grijstinten. |
| Format16bppRgb555 | n/a | Specificeert dat het pixelformaat 16 bits per pixel is met 5 bits voor elk van de rode, groene en blauwe componenten en dat het resterende bit niet wordt gebruikt. |
| Format16bppRgb565 | n/a | Specificeert dat het pixelformaat 16 bits per pixel is met 5 bits voor rood, 6 bits voor groen en 5 bits voor blauwe componenten. |
| Format16bppArgb1555 | n/a | Specificeert dat het pixelformaat 16 bits per pixel is met 5 bits voor elk van de rode, groene en blauwe componenten en 1 bit voor alpha. |
| Format24bppRgb | n/a | Specificeert dat het pixelformaat 24 bits per pixel is met 8 bits voor elk van de rode, groene en blauwe componenten. |
| Format32bppRgb | n/a | Specificeert dat het pixelformaat 32 bits per pixel is met 8 bits voor elk van de rode, groene en blauwe componenten en de resterende 8 bits niet worden gebruikt. |
| Format32bppArgb | n/a | Specificeert dat het pixelformaat 32 bits per pixel is met 8 bits voor elk van de rode, groene en blauwe componenten en 8 bits voor alpha. |
| Format32bppPArgb | n/a | Specificeert dat het pixelformaat 32 bits per pixel is met 8 bits voor elk van de rode, groene en blauwe componenten en 8 bits voor alpha. De rode, groene en blauwe componenten zijn vooraf vermenigvuldigd volgens de waarde van de alpha-component. |
| Format48bppRgb | n/a | Specificeert dat het pixelformaat 48 bits per pixel is met 16 bits voor elk van de rode, groene en blauwe componenten. |
| Format64bppArgb | n/a | Specificeert dat het pixelformaat 64 bits per pixel is met 16 bits voor elk van de rode, groene en blauwe componenten en 16 bits voor alpha. |
| Format64bppPArgb | n/a | Specificeert dat het pixelformaat 64 bits per pixel is met 16 bits voor elk van de rode, groene en blauwe componenten en 16 bits voor alpha. De rode, groene en blauwe componenten zijn vooraf vermenigvuldigd volgens de waarde van de alpha-component. |
| Format32bppCMYK | n/a | Specificeert dat het pixelformaat 32 bits per pixel is met 8 bits voor elk van de cyaan, magenta, geel en sleutelcomponenten. |
| Max | 16 | De maximale waarde van deze enum. |

## Zie ook

* Naamruimte [System::Drawing::Imaging](../)
* Bibliotheek [Aspose.Slides](../../)