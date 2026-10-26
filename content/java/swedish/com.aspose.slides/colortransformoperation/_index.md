---
title: ColorTransformOperation
second_title: Aspose.Slides för Java API-referens
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
| [Tint](#Tint) | Färgar färgen. |
| [Shade](#Shade) | Skuggar färgen. |
| [Complement](#Complement) | Ändrar färgen till en RGB-komplementär färg. |
| [Inverse](#Inverse) | Ändrar färgen till en inverterad färg. |
| [Grayscale](#Grayscale) | Ändrar färgen till en grå färg med samma ljusstyrka. |
| [SetAlpha](#SetAlpha) | Definierar en alfakomponent för färgen. |
| [AddAlpha](#AddAlpha) | Lägger till ett parametervärde till en alfakomponent för färgen. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplicerar en alfakomponent med ett parametervärde. |
| [SetHue](#SetHue) | Ändrar färgens nyanskomponent till ett parametervärde. |
| [AddHue](#AddHue) | Lägger till ett parametervärde till färgens nyanskomponent. |
| [MultiplyHue](#MultiplyHue) | Multiplicerar en nyanskomponent med ett parametervärde. |
| [SetSaturation](#SetSaturation) | Ändrar färgens mättnadskomponent till ett parametervärde. |
| [AddSaturation](#AddSaturation) | Lägger till ett parametervärde till färgens mättnadskomponent. |
| [MultiplySaturation](#MultiplySaturation) | Multiplicerar en mättnadskomponent med ett parametervärde. |
| [SetLuminance](#SetLuminance) | Ändrar färgens luminanskomponent till ett parametervärde. |
| [AddLuminance](#AddLuminance) | Lägger till ett parametervärde till färgens luminanskomponent. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplicerar en luminanskomponent med ett parametervärde. |
| [SetRed](#SetRed) | Ändrar färgens rödkomponent till ett parametervärde. |
| [AddRed](#AddRed) | Lägger till ett parametervärde till färgens rödkomponent. |
| [MultiplyRed](#MultiplyRed) | Multiplicerar en rödkomponent med ett parameter. |
| [SetGreen](#SetGreen) | Ändrar färgens grönkomponent till ett parametervärde. |
| [AddGreen](#AddGreen) | Lägger till ett parameter till färgens grönkomponent. |
| [MultiplyGreen](#MultiplyGreen) | Multiplicerar en grönkomponent med ett parametervärde. |
| [SetBlue](#SetBlue) | Ändrar färgens blåkomponent till ett parametervärde. |
| [AddBlue](#AddBlue) | Lägger till ett parametervärde till färgens blåkomponent. |
| [MultiplyBlue](#MultiplyBlue) | Multiplicerar en blåkomponent med ett parametervärde. |
| [Gamma](#Gamma) | Gamma-korrigering. |
| [InverseGamma](#InverseGamma) | Invers gamma-korrigering. |
### Tint {#Tint}
```
public static final int Tint
```

Färgar färgen. Parametern är i intervallet mellan 0 (originalfärg) och 1 (vit).

### Shade {#Shade}
```
public static final int Shade
```

Skuggar färgen. Parametern är i intervallet mellan 0 (originalfärg) och 1 (svart).

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

Definierar en alfakomponent för färgen. Parametern är i intervallet mellan 0 (transparent) och 1 (opak).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Lägger till ett parametervärde till en alfakomponent för färgen. Parametern är i intervallet mellan -1 och 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multiplicerar en alfakomponent med ett parametervärde.

### SetHue {#SetHue}
```
public static final int SetHue
```

Ändrar färgens nyanskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Lägger till ett parametervärde till färgens nyanskomponent. Parametern är i intervallet mellan -360 och 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multiplicerar en nyanskomponent med ett parametervärde.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Ändrar färgens mättnadskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Lägger till ett parametervärde till färgens mättnadskomponent. Parametern är i intervallet mellan -1 och 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multiplicerar en mättnadskomponent med ett parametervärde.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Ändrar färgens luminanskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Lägger till ett parametervärde till färgens luminanskomponent. Parametern är i intervallet mellan -1 och 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multiplicerar en luminanskomponent med ett parametervärde.

### SetRed {#SetRed}
```
public static final int SetRed
```

Ändrar färgens rödkomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Lägger till ett parametervärde till färgens rödkomponent. Parametern är i intervallet mellan -1 och 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multiplicerar en rödkomponent med ett parameter.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Ändrar färgens grönkomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Lägger till ett parameter till färgens grönkomponent. Parametern är i intervallet mellan -1 och 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multiplicerar en grönkomponent med ett parametervärde.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Ändrar färgens blåkomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Lägger till ett parametervärde till färgens blåkomponent. Parametern är i intervallet mellan -1 och 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multiplicerar en blåkomponent med ett parametervärde.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma-korrigering. Parametern ignoreras.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Invers gamma-korrigering. Parametern ignoreras.