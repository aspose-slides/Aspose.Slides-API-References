---
title: ColorTransformOperation
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert kleurtransformatie-operatie.
type: docs
weight: 5747
url: /nl/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Definieert kleurtransformatie-operatie.

```cpp
enum class ColorTransformOperation
```

### Values

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Tint | 0 | Tint de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (wit). |
| Shade | 1 | Schaduwt de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (zwart). |
| Complement | 2 | Verandert de kleur naar een RGB complementaire kleur. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Verandert de kleur naar een omgekeerde kleur. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Verandert de kleur naar een grijze kleur met dezelfde lichtheid. Parameter genegeerd. |
| SetAlpha | 5 | Definieert een alfacomponent van de kleur. Parameter ligt in het bereik tussen 0 (transparant) en 1 (ondoorzichtig). |
| AddAlpha | 6 | Voegt de waarde van een parameter toe aan een alfacomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplyAlpha | 7 | Vermenigvuldigt een alfacomponent met de waarde van een parameter. |
| SetHue | 8 | Verandert een tintcomponent van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360. |
| AddHue | 9 | Voegt de waarde van een parameter toe aan de tintcomponent van de kleur. Parameter ligt in het bereik tussen -360 en 360. |
| MultiplyHue | 10 | Vermenigvuldigt een tintcomponent met de waarde van een parameter. |
| SetSaturation | 11 | Verandert een verzadigingscomponent van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| AddSaturation | 12 | Voegt de waarde van een parameter toe aan een verzadigingscomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplySaturation | 13 | Vermenigvuldigt een verzadigingscomponent met de waarde van een parameter. |
| SetLuminance | 14 | Verandert een luminantiecomponent van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| AddLuminance | 15 | Voegt de waarde van een parameter toe aan een luminantiecomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplyLuminance | 16 | Vermenigvuldigt een luminantiecomponent met de waarde van een parameter. |
| SetRed | 17 | Verandert een rode component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| AddRed | 18 | Voegt de waarde van een parameter toe aan een rode component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplyRed | 19 | Vermenigvuldigt een rode component met een parameter. |
| SetGreen | 20 | Verandert een groene component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| AddGreen | 21 | Voegt een parameter toe aan een groene component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplyGreen | 22 | Vermenigvuldigt een groene component van de kleur met de waarde van een parameter. |
| SetBlue | 23 | Verandert een blauwe component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360. |
| AddBlue | 24 | Voegt de waarde van een parameter toe aan een blauwe component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MultiplyBlue | 25 | Vermenigvuldigt een blauwe component met de waarde van een parameter. |
| Gamma | 26 | Gamma-correctie. Parameter genegeerd. |
| InverseGamma | 27 | Inverse gamma-correctie. Parameter genegeerd. |

## Zie ook

* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)