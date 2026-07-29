---
title: PixelFormat
second_title: Aspose.Slides för C++ API-referens
description: Anger färgdataformatet för en pixel.
type: docs
weight: 326
url: /sv/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Anger färgdataformatet för en pixel.

```cpp
enum class PixelFormat
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Indexed | 65536 | Anger att pixeldata innehåller färgindexerade värden vilket betyder att de är ett index till färger i systemets färgtabell. |
| Gdi | 131072 | Anger att pixeldata innehåller GDI-färger. |
| Alpha | 262144 | Anger att pixeldata innehåller alfavärden som inte är förmultiplicerade. |
| PAlpha | 524288 | Anger att pixeldata innehåller förmultiplicerade alfavärden. |
| Extended | 1048576 | Reserverad. |
| Canonical | 2097152 | Anger pixelformatet med 32 bitar per pixel med 24-bitars färgdjup och en 8-bitars alfakanal. |
| Undefined | 0 | Anger att pixelformatet är odefinierat. |
| DontCare | 0 | Pixelformatet är inte specificerat. |
| Format1bppIndexed | n/a | Anger att pixelformatet är 1 bit per pixel med indexerad färg. |
| Format4bppIndexed | n/a | Anger att pixelformatet är 4 bitar per pixel med indexerad färg. |
| Format8bppIndexed | n/a | Anger att pixelformatet är 8 bitar per pixel med indexerad färg. |
| Format16bppGrayScale | n/a | Anger att pixelformatet är 16 bitar per pixel. Färginformationen specificerar 65536 nyanser av grått. |
| Format16bppRgb555 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för varje röd, grön och blå komponent och den återstående biten används inte. |
| Format16bppRgb565 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå komponenter. |
| Format16bppArgb1555 | n/a | Anger att pixelformatet är 16 bitar per pixel med 5 bitar för varje röd, grön och blå komponent samt 1 bit för alfa. |
| Format24bppRgb | n/a | Anger att pixelformatet är 24 bitar per pixel med 8 bitar för varje röd, grön och blå komponent. |
| Format32bppRgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje röd, grön och blå komponent och de återstående 8 bitarna används inte. |
| Format32bppArgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje röd, grön och blå komponent samt 8 bitar för alfa. |
| Format32bppPArgb | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje röd, grön och blå komponent samt 8 bitar för alfa. De röda, gröna och blå komponenterna är förmultiplicerade enligt alfab komponentens värde. |
| Format48bppRgb | n/a | Anger att pixelformatet är 48 bitar per pixel med 16 bitar för varje röd, grön och blå komponent. |
| Format64bppArgb | n/a | Anger att pixelformatet är 64 bitar per pixel med 16 bitar för varje röd, grön och blå komponent samt 16 bitar för alfa. |
| Format64bppPArgb | n/a | Anger att pixelformatet är 64 bitar per pixel med 16 bitar för varje röd, grön och blå komponent samt 16 bitar för alfa. De röda, gröna och blå komponenterna är förmultiplicerade enligt alfab komponentens värde. |
| Format32bppCMYK | n/a | Anger att pixelformatet är 32 bitar per pixel med 8 bitar för varje cyan, magenta, gul och nyckelkomponent. |
| Max | 16 | Det maximala värdet för denna enum. |

## Se även

* Namnrymd [System::Drawing::Imaging](../)
* Bibliotek [Aspose.Slides](../../)