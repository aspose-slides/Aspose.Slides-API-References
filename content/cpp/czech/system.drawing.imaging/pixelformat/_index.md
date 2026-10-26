---
title: PixelFormat
second_title: Aspose.Slides pro C++ API referenci
description: Určuje formát barevných dat pixelu.
type: docs
weight: 326
url: /cs/system.drawing.imaging/pixelformat/
---
## PixelFormat výčet

Specifikuje formát barevných dat pixelu.

```cpp
enum class PixelFormat
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Indexed | 65536 | Určuje, že pixelová data obsahují indexované barevné hodnoty, což znamená, že jsou indexem do barev v systémové barevné tabulce. |
| Gdi | 131072 | Určuje, že pixelová data obsahují barvy GDI. |
| Alpha | 262144 | Určuje, že pixelová data obsahují alfa hodnoty, které nejsou předem násobeny. |
| PAlpha | 524288 | Určuje, že pixelová data obsahují předem násobené alfa hodnoty. |
| Extended | 1048576 | Vyhrazeno. |
| Canonical | 2097152 | Určuje formát pixelu 32 bitů na pixel se 24bitovou hloubkou barev a 8bitovým alfa kanálem. |
| Undefined | 0 | Určuje, že formát pixelu není definován. |
| DontCare | 0 | Formát pixelu není specifikován. |
| Format1bppIndexed | n/a | Určuje, že formát pixelu je 1 bit na pixel s indexovanou barvou. |
| Format4bppIndexed | n/a | Určuje, že formát pixelu je 4 bity na pixel s indexovanou barvou. |
| Format8bppIndexed | n/a | Určuje, že formát pixelu je 8 bitů na pixel s indexovanou barvou. |
| Format16bppGrayScale | n/a | Určuje, že formát pixelu je 16 bitů na pixel. Barevná informace udává 65536 odstínů šedé. |
| Format16bppRgb555 | n/a | Určuje, že formát pixelu je 16 bitů na pixel s 5 bity pro každou ze složek červené, zelené a modré a zbývající bit není použit. |
| Format16bppRgb565 | n/a | Určuje, že formát pixelu je 16 bitů na pixel s 5 bity pro červenou, 6 bity pro zelenou a 5 bity pro modrou složku. |
| Format16bppArgb1555 | n/a | Určuje, že formát pixelu je 16 bitů na pixel s 5 bity pro každou ze složek červené, zelené a modré a 1 bitem pro alfa. |
| Format24bppRgb | n/a | Určuje, že formát pixelu je 24 bitů na pixel s 8 bity pro každou ze složek červené, zelené a modré. |
| Format32bppRgb | n/a | Určuje, že formát pixelu je 32 bitů na pixel s 8 bity pro každou ze složek červené, zelené a modré a zbývajících 8 bitů není použito. |
| Format32bppArgb | n/a | Určuje, že formát pixelu je 32 bitů na pixel s 8 bity pro každou ze složek červené, zelené a modré a 8 bity pro alfa. |
| Format32bppPArgb | n/a | Určuje, že formát pixelu je 32 bitů na pixel s 8 bity pro každou ze složek červené, zelené a modré a 8 bity pro alfa. Složky červené, zelené a modré jsou předem násobeny podle hodnoty alfa složky. |
| Format48bppRgb | n/a | Určuje, že formát pixelu je 48 bitů na pixel s 16 bity pro každou ze složek červené, zelené a modré. |
| Format64bppArgb | n/a | Určuje, že formát pixelu je 64 bitů na pixel s 16 bity pro každou ze složek červené, zelené a modré a 16 bity pro alfa. |
| Format64bppPArgb | n/a | Určuje, že formát pixelu je 64 bitů na pixel s 16 bity pro každou ze složek červené, zelené a modré a 16 bity pro alfa. Složky červené, zelené a modré jsou předem násobeny podle hodnoty alfa složky. |
| Format32bppCMYK | n/a | Určuje, že formát pixelu je 32 bitů na pixel s 8 bity pro každou ze složek azurové, purpurové, žluté a klíčové. |
| Max | 16 | Maximální hodnota tohoto výčtu. |

## Viz také

* Jmenný prostor [System::Drawing::Imaging](../)
* Knihovna [Aspose.Slides](../../)