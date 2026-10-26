---
title: ColorTransformOperation
second_title: Aspose.Slides voor Android via Java API-referentie
description: Definieert kleurtransformatieoperatie.
type: docs
url: /nl/com.aspose.slides/colortransformoperation/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definieert een kleurtransformatieoperatie.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Tint](#Tint) | Tint de kleur. |
| [Shade](#Shade) | Schaduwt de kleur. |
| [Complement](#Complement) | Verandert de kleur in een RGB-complementaire kleur. |
| [Inverse](#Inverse) | Verandert de kleur in een omgekeerde kleur. |
| [Grayscale](#Grayscale) | Verandert de kleur in een grijze kleur met dezelfde lichtheid. |
| [SetAlpha](#SetAlpha) | Definieert een alfacomponent van de kleur. |
| [AddAlpha](#AddAlpha) | Voegt de waarde van een parameter toe aan een alfacomponent van de kleur. |
| [MultiplyAlpha](#MultiplyAlpha) | Vermenigvuldigt een alfacomponent met de waarde van een parameter. |
| [SetHue](#SetHue) | Verandert een hue-component van de kleur naar de waarde van een parameter. |
| [AddHue](#AddHue) | Voegt de waarde van een parameter toe aan de hue-component van de kleur. |
| [MultiplyHue](#MultiplyHue) | Vermenigvuldigt een hue-component met de waarde van een parameter. |
| [SetSaturation](#SetSaturation) | Verandert een saturatiecomponent van de kleur naar de waarde van een parameter. |
| [AddSaturation](#AddSaturation) | Voegt de waarde van een parameter toe aan een saturatiecomponent van de kleur. |
| [MultiplySaturation](#MultiplySaturation) | Vermenigvuldigt een saturatiecomponent met de waarde van een parameter. |
| [SetLuminance](#SetLuminance) | Verandert een luminantiecomponent van de kleur naar de waarde van een parameter. |
| [AddLuminance](#AddLuminance) | Voegt de waarde van een parameter toe aan een luminantiecomponent van de kleur. |
| [MultiplyLuminance](#MultiplyLuminance) | Vermenigvuldigt een luminantiecomponent met de waarde van een parameter. |
| [SetRed](#SetRed) | Verandert een rode component van de kleur naar de waarde van een parameter. |
| [AddRed](#AddRed) | Voegt de waarde van een parameter toe aan een rode component van de kleur. |
| [MultiplyRed](#MultiplyRed) | Vermenigvuldigt een rode component met een parameter. |
| [SetGreen](#SetGreen) | Verandert een groene component van de kleur naar de waarde van een parameter. |
| [AddGreen](#AddGreen) | Voegt een parameter toe aan een groene component van de kleur. |
| [MultiplyGreen](#MultiplyGreen) | Vermenigvuldigt een groene component van de kleur met de waarde van een parameter. |
| [SetBlue](#SetBlue) | Verandert een blauwe component van de kleur naar de waarde van een parameter. |
| [AddBlue](#AddBlue) | Voegt de waarde van een parameter toe aan een blauwe component van de kleur. |
| [MultiplyBlue](#MultiplyBlue) | Vermenigvuldigt een blauwe component van de kleur met de waarde van een parameter. |
| [Gamma](#Gamma) | Gamma-correctie. |
| [InverseGamma](#InverseGamma) | Inverse gamma-correctie. |
### Tint {#Tint}
```
public static final int Tint
```


Tint de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (wit).

### Shade {#Shade}
```
public static final int Shade
```


Schaduwt de kleur. Parameter ligt in het bereik tussen 0 (originele kleur) en 1 (zwart).

### Complement {#Complement}
```
public static final int Complement
```


Verandert de kleur in een RGB-complementaire kleur. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```


Verandert de kleur in een omgekeerde kleur. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Verandert de kleur in een grijze kleur met dezelfde lichtheid. Parameter wordt genegeerd.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```


Definieert een alfacomponent van de kleur. Parameter ligt in het bereik tussen 0 (transparant) en 1 (ondoorzichtig).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```


Voegt de waarde van een parameter toe aan een alfacomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```


Vermenigvuldigt een alfacomponent met de waarde van een parameter.

### SetHue {#SetHue}
```
public static final int SetHue
```


Verandert een hue-component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360.

### AddHue {#AddHue}
```
public static final int AddHue
```


Voegt de waarde van een parameter toe aan de hue-component van de kleur. Parameter ligt in het bereik tussen -360 en 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```


Vermenigvuldigt een hue-component met de waarde van een parameter.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```


Verandert een saturatiecomponent van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```


Voegt de waarde van een parameter toe aan een saturatiecomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```


Vermenigvuldigt een saturatiecomponent met de waarde van een parameter.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```


Verandert een luminantiecomponent van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```


Voegt de waarde van een parameter toe aan een luminantiecomponent van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```


Vermenigvuldigt een luminantiecomponent met de waarde van een parameter.

### SetRed {#SetRed}
```
public static final int SetRed
```


Verandert een rode component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1.

### AddRed {#AddRed}
```
public static final int AddRed
```


Voegt de waarde van een parameter toe aan een rode component van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```


Vermenigvuldigt een rode component met een parameter.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```


Verandert een groene component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```


Voegt een parameter toe aan een groene component van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```


Vermenigvuldigt een groene component van de kleur met de waarde van een parameter.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```


Verandert een blauwe component van de kleur naar de waarde van een parameter. Parameter ligt in het bereik tussen 0 en 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```


Voegt de waarde van een parameter toe aan een blauwe component van de kleur. Parameter ligt in het bereik tussen -1 en 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```


Vermenigvuldigt een blauwe component van de kleur met de waarde van een parameter.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma-correctie. Parameter wordt genegeerd.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```


Inverse gamma-correctie. Parameter wordt genegeerd.