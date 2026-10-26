---
title: ColorTransformOperation
second_title: Aspose.Slides für C++ API Referenz
description: Definiert eine Farbtransformationsoperation.
type: docs
weight: 5747
url: /de/aspose.slides/colortransformoperation/
---
## ColorTransformOperation Enum

Definiert eine Farbtransformationsoperation.

```cpp
enum class ColorTransformOperation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Tint | 0 | Färbt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Weiß). |
| Shade | 1 | Verdunkelt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Schwarz). |
| Complement | 2 | Ändert die Farbe zu einer komplementären RGB-Farbe. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Ändert die Farbe zu einer invertierten Farbe. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Ändert die Farbe zu einem Grauton mit gleicher Helligkeit. Parameter wird ignoriert. |
| SetAlpha | 5 | Definiert die Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen 0 (transparent) und 1 (undurchsichtig). |
| AddAlpha | 6 | Addiert den Wert des Parameters zur Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplyAlpha | 7 | Multipliziert die Alpha-Komponente mit dem Wert des Parameters. |
| SetHue | 8 | Ändert die Farbtonkomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 360. |
| AddHue | 9 | Addiert den Wert des Parameters zur Farbtonkomponente der Farbe. Der Parameter liegt im Bereich zwischen -360 und 360. |
| MultiplyHue | 10 | Multipliziert die Farbtonkomponente mit dem Wert des Parameters. |
| SetSaturation | 11 | Ändert die Sättigungskomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| AddSaturation | 12 | Addiert den Wert des Parameters zur Sättigungskomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplySaturation | 13 | Multipliziert die Sättigungskomponente mit dem Wert des Parameters. |
| SetLuminance | 14 | Ändert die Luminanzkomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| AddLuminance | 15 | Addiert den Wert des Parameters zur Luminanzkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplyLuminance | 16 | Multipliziert die Luminanzkomponente mit dem Wert des Parameters. |
| SetRed | 17 | Ändert die Rotkomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| AddRed | 18 | Addiert den Wert des Parameters zur Rotkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplyRed | 19 | Multipliziert die Rotkomponente mit dem Parameter. |
| SetGreen | 20 | Ändert die Grünkomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| AddGreen | 21 | Addiert einen Parameter zur Grünkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplyGreen | 22 | Multipliziert die Grünkomponente der Farbe mit dem Wert des Parameters. |
| SetBlue | 23 | Ändert die Blaukomponente der Farbe auf den Wert des Parameters. Der Parameter liegt im Bereich zwischen 0 und 360. |
| AddBlue | 24 | Addiert den Wert des Parameters zur Blaukomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MultiplyBlue | 25 | Multipliziert die Blaukomponente der Farbe mit dem Wert des Parameters. |
| Gamma | 26 | Gammakorrektur. Parameter wird ignoriert. |
| InverseGamma | 27 | Inverse Gammakorrektur. Parameter wird ignoriert. |

## Siehe auch

* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)