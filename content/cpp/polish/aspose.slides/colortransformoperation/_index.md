---
title: ColorTransformOperation
second_title: Aspose.Slides dla interfejsu API C++
description: Definiuje operację przekształcenia koloru.
type: docs
weight: 5747
url: /pl/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Definiuje operację przekształcenia koloru.

```cpp
enum class ColorTransformOperation
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Tint | 0 | Tonuje kolor. Parametr znajduje się w przedziale od 0 (oryginalny kolor) do 1 (biały). |
| Shade | 1 | Cieniuje kolor. Parametr znajduje się w przedziale od 0 (oryginalny kolor) do 1 (czarny). |
| Complement | 2 | Zmienia kolor na komplementarny w przestrzeni RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Zmienia kolor na odwrócony. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Zmienia kolor na szary o tej samej jasności. Parametr jest ignorowany. |
| SetAlpha | 5 | Definiuje składnik alfa koloru. Parametr znajduje się w przedziale od 0 (przezroczysty) do 1 (nieprzezroczysty). |
| AddAlpha | 6 | Dodaje wartość parametru do składnika alfa koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplyAlpha | 7 | Mnoży składnik alfa przez wartość parametru. |
| SetHue | 8 | Zmienia składnik odcienia koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 360. |
| AddHue | 9 | Dodaje wartość parametru do składnika odcienia koloru. Parametr znajduje się w przedziale od -360 do 360. |
| MultiplyHue | 10 | Mnoży składnik odcienia przez wartość parametru. |
| SetSaturation | 11 | Zmienia składnik nasycenia koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1. |
| AddSaturation | 12 | Dodaje wartość parametru do składnika nasycenia koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplySaturation | 13 | Mnoży składnik nasycenia przez wartość parametru. |
| SetLuminance | 14 | Zmienia składnik luminancji koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1. |
| AddLuminance | 15 | Dodaje wartość parametru do składnika luminancji koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplyLuminance | 16 | Mnoży składnik luminancji przez wartość parametru. |
| SetRed | 17 | Zmienia składnik czerwonego koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1. |
| AddRed | 18 | Dodaje wartość parametru do składnika czerwonego koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplyRed | 19 | Mnoży składnik czerwonego koloru przez parametr. |
| SetGreen | 20 | Zmienia składnik zielonego koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1. |
| AddGreen | 21 | Dodaje parametr do składnika zielonego koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplyGreen | 22 | Mnoży składnik zielonego koloru przez wartość parametru. |
| SetBlue | 23 | Zmienia składnik niebieskiego koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 360. |
| AddBlue | 24 | Dodaje wartość parametru do składnika niebieskiego koloru. Parametr znajduje się w przedziale od -1 do 1. |
| MultiplyBlue | 25 | Mnoży składnik niebieskiego koloru przez wartość parametru. |
| Gamma | 26 | Korekcja gamma. Parametr jest ignorowany. |
| InverseGamma | 27 | Odwrócona korekcja gamma. Parametr jest ignorowany. |

## See Also

* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)