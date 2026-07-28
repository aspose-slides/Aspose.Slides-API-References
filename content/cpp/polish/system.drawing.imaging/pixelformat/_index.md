---
title: PixelFormat
second_title: Aspose.Slides dla referencji API C++
description: Określa format danych koloru piksela.
type: docs
weight: 326
url: /pl/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Określa format danych kolorów piksela.

```cpp
enum class PixelFormat
```

### Wartości

| Name | Value | Description |
| --- | --- | --- |
| Indexed | 65536 | Określa, że dane piksela zawierają wartości indeksowane kolorami, co oznacza, że są indeksami do kolorów w systemowej tabeli kolorów. |
| Gdi | 131072 | Określa, że dane piksela zawierają kolory GDI. |
| Alpha | 262144 | Określa, że dane piksela zawierają wartości alfa, które nie są wstępnie pomnożone. |
| PAlpha | 524288 | Określa, że dane piksela zawierają wstępnie pomnożone wartości alfa. |
| Extended | 1048576 | Zarezerwowane. |
| Canonical | 2097152 | Określa format piksela 32 bity na piksel z 24-bitową głębią koloru i 8-bitowym kanałem alfa. |
| Undefined | 0 | Określa, że format piksela jest niezdefiniowany. |
| DontCare | 0 | Format piksela nie jest określony. |
| Format1bppIndexed | n/a | Określa, że format piksela to 1-bitowy indeksowany kolor. |
| Format4bppIndexed | n/a | Określa, że format piksela to 4-bitowy indeksowany kolor. |
| Format8bppIndexed | n/a | Określa, że format piksela to 8-bitowy indeksowany kolor. |
| Format16bppGrayScale | n/a | Określa, że format piksela to 16 bitów na piksel. Informacje o kolorze określają 65536 odcieni szarości. |
| Format16bppRgb555 | n/a | Określa, że format piksela to 16 bitów na piksel z 5 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz nieużywanym pozostałym bitem. |
| Format16bppRgb565 | n/a | Określa, że format piksela to 16 bitów na piksel z 5 bitami dla czerwonego, 6 bitami dla zielonego i 5 bitami dla niebieskiego komponentu. |
| Format16bppArgb1555 | n/a | Określa, że format piksela to 16 bitów na piksel z 5 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz 1 bitem dla alfa. |
| Format24bppRgb | n/a | Określa, że format piksela to 24 bity na piksel z 8 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego. |
| Format32bppRgb | n/a | Określa, że format piksela to 32 bity na piksel z 8 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz nieużywanymi 8 bitami. |
| Format32bppArgb | n/a | Określa, że format piksela to 32 bity na piksel z 8 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz 8 bitami dla alfa. |
| Format32bppPArgb | n/a | Określa, że format piksela to 32 bity na piksel z 8 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz 8 bitami dla alfa. Składowe czerwony, zielony i niebieski są wstępnie pomnożone zgodnie z wartością komponentu alfa. |
| Format48bppRgb | n/a | Określa, że format piksela to 48 bitów na piksel z 16 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego. |
| Format64bppArgb | n/a | Określa, że format piksela to 64 bity na piksel z 16 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz 16 bitami dla alfa. |
| Format64bppPArgb | n/a | Określa, że format piksela to 64 bity na piksel z 16 bitami dla każdego z komponentów czerwonego, zielonego i niebieskiego oraz 16 bitami dla alfa. Składowe czerwony, zielony i niebieski są wstępnie pomnożone zgodnie z wartością komponentu alfa. |
| Format32bppCMYK | n/a | Określa, że format piksela to 32 bity na piksel z 8 bitami dla każdego z komponentów cyjan, magenta, żółty i czarny. |
| Max | 16 | Maksymalna wartość tego wyliczenia. |

## Zobacz także

* Przestrzeń nazw [System::Drawing::Imaging](../)
* Biblioteka [Aspose.Slides](../../)