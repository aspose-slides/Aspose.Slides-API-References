---
title: ColorTransformOperation
second_title: Aspose.Slides för C++ API-referens
description: Definierar färgtransformationsoperation.
type: docs
weight: 5747
url: /sv/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Definierar färgtransformationsoperation.

```cpp
enum class ColorTransformOperation
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Tint | 0 | Tonar färgen. Parametern är i intervallet mellan 0 (originalfärg) och 1 (vit). |
| Shade | 1 | Skuggar färgen. Parametern är i intervallet mellan 0 (originalfärg) och 1 (svart). |
| Complement | 2 | Ändrar färgen till en RGB-komplementär. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Ändrar färgen till en inverterad färg. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Ändrar färgen till en grå nyans med samma ljusstyrka. Parametern ignoreras. |
| SetAlpha | 5 | Definierar en alfa-komponent i färgen. Parametern är i intervallet mellan 0 (transparent) och 1 (opak). |
| AddAlpha | 6 | Lägger till en parameters värde till en alfa-komponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplyAlpha | 7 | Multiplicerar en alfa-komponent med en parameters värde. |
| SetHue | 8 | Ändrar en nyanskomponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 360. |
| AddHue | 9 | Lägger till en parameters värde till nyanskomponenten i färgen. Parametern är i intervallet mellan -360 och 360. |
| MultiplyHue | 10 | Multiplicerar en nyanskomponent med en parameters värde. |
| SetSaturation | 11 | Ändrar en mättnadskomponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 1. |
| AddSaturation | 12 | Lägger till en parameters värde till en mättnadskomponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplySaturation | 13 | Multiplicerar en mättnadskomponent med en parameters värde. |
| SetLuminance | 14 | Ändrar en luminanskomponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 1. |
| AddLuminance | 15 | Lägger till en parameters värde till en luminanskomponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplyLuminance | 16 | Multiplicerar en luminanskomponent med en parameters värde. |
| SetRed | 17 | Ändrar en röd komponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 1. |
| AddRed | 18 | Lägger till en parameters värde till en röd komponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplyRed | 19 | Multiplicerar en röd komponent med en parameter. |
| SetGreen | 20 | Ändrar en grön komponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 1. |
| AddGreen | 21 | Lägger till en parameter till en grön komponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplyGreen | 22 | Multiplicerar en grön komponent med en parameters värde. |
| SetBlue | 23 | Ändrar en blå komponent i färgen till en parameters värde. Parametern är i intervallet mellan 0 och 360. |
| AddBlue | 24 | Lägger till en parameters värde till en blå komponent i färgen. Parametern är i intervallet mellan -1 och 1. |
| MultiplyBlue | 25 | Multiplicerar en blå komponent med en parameters värde. |
| Gamma | 26 | Gamma-korrigering. Parametern ignoreras. |
| InverseGamma | 27 | Inverterad gamma-korrigering. Parametern ignoreras. |

## Se även

* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)