---
title: ColorTransformOperation
second_title: Aspose.Slides för Android via Java API-referens
description: Definierar färgtransformationsoperation.
type: docs
url: /sv/com.aspose.slides/colortransformoperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definierar färgtransformationsoperation.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Tint](#Tint) | Tonar färgen. |
| [Shade](#Shade) | Skuggar färgen. |
| [Complement](#Complement) | Ändrar färgen till en RGB-komplementär färg. |
| [Inverse](#Inverse) | Ändrar färgen till en inverterad färg. |
| [Grayscale](#Grayscale) | Ändrar färgen till en grå färg med samma ljusstyrka. |
| [SetAlpha](#SetAlpha) | Definierar en alfa-komponent för färgen. |
| [AddAlpha](#AddAlpha) | Lägger till ett parametervärde till alfa-komponenten för färgen. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplicerar alfa-komponenten med ett parametervärde. |
| [SetHue](#SetHue) | Ändrar nyanskomponenten i färgen till ett parametervärde. |
| [AddHue](#AddHue) | Lägger till ett parametervärde till nyanskomponenten i färgen. |
| [MultiplyHue](#MultiplyHue) | Multiplicerar nyanskomponenten med ett parametervärde. |
| [SetSaturation](#SetSaturation) | Ändrar mättnadskomponenten i färgen till ett parametervärde. |
| [AddSaturation](#AddSaturation) | Lägger till ett parametervärde till mättnadskomponenten i färgen. |
| [MultiplySaturation](#MultiplySaturation) | Multiplicerar mättnadskomponenten med ett parametervärde. |
| [SetLuminance](#SetLuminance) | Ändrar luminanskomponenten i färgen till ett parametervärde. |
| [AddLuminance](#AddLuminance) | Lägger till ett parametervärde till luminanskomponenten i färgen. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplicerar luminanskomponenten med ett parametervärde. |
| [SetRed](#SetRed) | Ändrar den röda komponenten i färgen till ett parametervärde. |
| [AddRed](#AddRed) | Lägger till ett parametervärde till den röda komponenten i färgen. |
| [MultiplyRed](#MultiplyRed) | Multiplicerar den röda komponenten med ett parametervärde. |
| [SetGreen](#SetGreen) | Ändrar den gröna komponenten i färgen till ett parametervärde. |
| [AddGreen](#AddGreen) | Lägger till ett parametervärde till den gröna komponenten i färgen. |
| [MultiplyGreen](#MultiplyGreen) | Multiplicerar den gröna komponenten med ett parametervärde. |
| [SetBlue](#SetBlue) | Ändrar den blåa komponenten i färgen till ett parametervärde. |
| [AddBlue](#AddBlue) | Lägger till ett parametervärde till den blåa komponenten i färgen. |
| [MultiplyBlue](#MultiplyBlue) | Multiplicerar den blåa komponenten med ett parametervärde. |
| [Gamma](#Gamma) | Gamma-korrektion. |
| [InverseGamma](#InverseGamma) | Inverterad gamma-korrektion. |
### Tint {#Tint}
```
public static final int Tint
```

Tonar färgen. Parametern är i intervallet mellan 0 (original färg) och 1 (vitt).

### Shade {#Shade}
```
public static final int Shade
```

Skuggar färgen. Parametern är i intervallet mellan 0 (original färg) och 1 (svart).

### Complement {#Complement}
```
public static final int Complement
```

Ändrar färgen till en RGB-komplementär färg. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Ändrar färgen till en inverterad färg. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Ändrar färgen till en grå färg med samma ljusstyrka. Parametern ignoreras.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Definierar en alfa-komponent för färgen. Parametern är i intervallet mellan 0 (transparent) och 1 (opak).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Lägger till ett parametervärde till alfa-komponenten för färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multiplicerar alfa-komponenten med ett parametervärde.

### SetHue {#SetHue}
```
public static final int SetHue
```

Ändrar nyanskomponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Lägger till ett parametervärde till nyanskomponenten i färgen. Parametern är i intervallet mellan -360 och 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multiplicerar nyanskomponenten med ett parametervärde.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Ändrar mättnadskomponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Lägger till ett parametervärde till mättnadskomponenten i färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multiplicerar mättnadskomponenten med ett parametervärde.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Ändrar luminanskomponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Lägger till ett parametervärde till luminanskomponenten i färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multiplicerar luminanskomponenten med ett parametervärde.

### SetRed {#SetRed}
```
public static final int SetRed
```

Ändrar den röda komponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Lägger till ett parametervärde till den röda komponenten i färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multiplicerar den röda komponenten med ett parametervärde.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Ändrar den gröna komponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Lägger till ett parametervärde till den gröna komponenten i färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multiplicerar den gröna komponenten med ett parametervärde.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Ändrar den blåa komponenten i färgen till ett parametervärde. Parametern är i intervallet mellan 0 och 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Lägger till ett parametervärde till den blåa komponenten i färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multiplicerar den blåa komponenten med ett parametervärde.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma-korrektion. Parametern ignoreras.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Inverterad gamma-korrektion. Parametern ignoreras.