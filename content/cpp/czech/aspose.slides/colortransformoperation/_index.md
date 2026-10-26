---
title: ColorTransformOperation
second_title: Aspose.Slides pro C++ referenční příručku API
description: Definuje operaci transformace barvy.
type: docs
weight: 5747
url: /cs/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum


Definuje operaci transformace barvy.

```cpp
enum class ColorTransformOperation
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Tint | 0 | Zabarvuje barvu. Parametr je v rozsahu mezi 0 (původní barva) a 1 (bílá). |
| Shade | 1 | Stíní barvu. Parametr je v rozsahu mezi 0 (původní barva) a 1 (černá). |
| Complement | 2 | Mění barvu na RGB komplementární. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Mění barvu na invertovanou barvu. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Mění barvu na šedou s tím samým jasem. Parametr je ignorován. |
| SetAlpha | 5 | Definuje alfa komponentu barvy. Parametr je v rozsahu mezi 0 (průhledná) a 1 (neprůhledná). |
| AddAlpha | 6 | Přidá hodnotu parametru k alfa komponentě barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplyAlpha | 7 | Vynásobí alfa komponentu hodnotou parametru. |
| SetHue | 8 | Mění komponentu odstínu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 360. |
| AddHue | 9 | Přidá hodnotu parametru ke komponentě odstínu barvy. Parametr je v rozsahu mezi -360 a 360. |
| MultiplyHue | 10 | Vynásobí komponentu odstínu hodnotou parametru. |
| SetSaturation | 11 | Mění komponentu saturace barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1. |
| AddSaturation | 12 | Přidá hodnotu parametru ke komponentě saturace barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplySaturation | 13 | Vynásobí komponentu saturace hodnotou parametru. |
| SetLuminance | 14 | Mění komponentu luminance barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1. |
| AddLuminance | 15 | Přidá hodnotu parametru ke komponentě luminance barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplyLuminance | 16 | Vynásobí komponentu luminance hodnotou parametru. |
| SetRed | 17 | Mění červenou komponentu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1. |
| AddRed | 18 | Přidá hodnotu parametru k červené komponentě barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplyRed | 19 | Vynásobí červenou komponentu parametrem. |
| SetGreen | 20 | Mění zelenou komponentu barvy na hodnotu parametru value. Parametr je v rozsahu mezi 0 a 1. |
| AddGreen | 21 | Přidá parametr k zelené komponentě barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplyGreen | 22 | Vynásobí zelenou komponentu barvy hodnotou parametru. |
| SetBlue | 23 | Mění modrou komponentu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 360. |
| AddBlue | 24 | Přidá hodnotu parametru k modré komponentě barvy. Parametr je v rozsahu mezi -1 a 1. |
| MultiplyBlue | 25 | Vynásobí modrou komponentu barvy hodnotou parametru. |
| Gamma | 26 | Gamma korekce. Parametr je ignorován. |
| InverseGamma | 27 | Inverzní gamma korekce. Parametr je ignorován. |

## Viz také

* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)