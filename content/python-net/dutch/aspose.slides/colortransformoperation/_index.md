---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumeratie

Definieert kleurtransformatie-operatie.

Het type ColorTransformOperation biedt de volgende leden:

## Velden

| Veld | Beschrijving |
| :- | :- |
| TINT | Tint de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (wit). |
| SHADE | Schaduwt de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (zwart). |
| COMPLEMENT | Verandert de kleur naar een RGB-complementaire kleur.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Verandert de kleur naar een omgekeerde kleur.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Verandert de kleur naar een grijze kleur met dezelfde helderheid. Parameter wordt genegeerd. |
| SET_ALPHA | Definieert een alfacomponent van de kleur. Parameter ligt in het bereik tussen 0 (transparant) en 1 (ondoorzichtig). |
| ADD_ALPHA | Voegt de waarde van een parameter toe aan een alfacomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_ALPHA | Vermenigvuldigt een alfacomponent met de waarde van een parameter. |
| SET_HUE | Verandert een hue-component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360. |
| ADD_HUE | Voegt de waarde van een parameter toe aan de hue-component van de kleur. Parameter ligt in het bereik tussen -360 en 360. |
| MULTIPLY_HUE | Vermenigvuldigt een hue-component met de waarde van een parameter. |
| SET_SATURATION | Verandert een saturatie-component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| ADD_SATURATION | Voegt de waarde van een parameter toe aan een saturatie-component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_SATURATION | Vermenigvuldigt een saturatie-component met de waarde van een parameter. |
| SET_LUMINANCE | Verandert een luminantie-component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| ADD_LUMINANCE | Voegt de waarde van een parameter toe aan een luminantie-component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_LUMINANCE | Vermenigvuldigt een luminantie-component met de waarde van een parameter. |
| SET_RED | Verandert een rode component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| ADD_RED | Voegt de waarde van een parameter toe aan een rode component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_RED | Vermenigvuldigt een rode component met een parameter. |
| SET_GREEN | Verandert een groene component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1. |
| ADD_GREEN | Voegt een parameter toe aan een groene component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_GREEN | Vermenigvuldigt een groene component met de waarde van een parameter. |
| SET_BLUE | Verandert een blauwe component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360. |
| ADD_BLUE | Voegt de waarde van een parameter toe aan een blauwe component van de kleur. Parameter ligt in het bereik tussen -1 en 1. |
| MULTIPLY_BLUE | Vermenigvuldigt een blauwe component met de waarde van een parameter. |
| GAMMA | Gamma-correctie. Parameter wordt genegeerd. |
| INVERSE_GAMMA | Inverse gamma-correctie. Parameter wordt genegeerd. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)