---
title: ColorTransformOperation
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Definuje operaci transformace barvy.
type: docs
url: /cs/com.aspose.slides/colortransformoperation/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definuje operaci transformace barvy.
## Pole

| Pole | Popis |
| --- | --- |
| [Tint](#Tint) | Zesvětluje barvu. |
| [Shade](#Shade) | Ztmaví barvu. |
| [Complement](#Complement) | Změní barvu na doplňkovou RGB barvu. |
| [Inverse](#Inverse) | Změní barvu na invertovanou barvu. |
| [Grayscale](#Grayscale) | Změní barvu na šedou se stejnou světlostí. |
| [SetAlpha](#SetAlpha) | Definuje alfa komponentu barvy. |
| [AddAlpha](#AddAlpha) | Přidá hodnotu parametru k alfa komponentě barvy. |
| [MultiplyAlpha](#MultiplyAlpha) | Vynásobí alfa komponentu hodnotou parametru. |
| [SetHue](#SetHue) | Změní komponentu odstínu barvy na hodnotu parametru. |
| [AddHue](#AddHue) | Přidá hodnotu parametru k komponentě odstínu barvy. |
| [MultiplyHue](#MultiplyHue) | Vynásobí komponentu odstínu hodnotou parametru. |
| [SetSaturation](#SetSaturation) | Změní komponentu sytosti barvy na hodnotu parametru. |
| [AddSaturation](#AddSaturation) | Přidá hodnotu parametru k komponentě sytosti barvy. |
| [MultiplySaturation](#MultiplySaturation) | Vynásobí komponentu sytosti hodnotou parametru. |
| [SetLuminance](#SetLuminance) | Změní komponentu jasu barvy na hodnotu parametru. |
| [AddLuminance](#AddLuminance) | Přidá hodnotu parametru k komponentě jasu barvy. |
| [MultiplyLuminance](#MultiplyLuminance) | Vynásobí komponentu jasu hodnotou parametru. |
| [SetRed](#SetRed) | Změní červenou komponentu barvy na hodnotu parametru. |
| [AddRed](#AddRed) | Přidá hodnotu parametru k červené komponentě barvy. |
| [MultiplyRed](#MultiplyRed) | Vynásobí červenou komponentu parametrem. |
| [SetGreen](#SetGreen) | Změní zelenou komponentu barvy na hodnotu parametru. |
| [AddGreen](#AddGreen) | Přidá parametr k zelené komponentě barvy. |
| [MultiplyGreen](#MultiplyGreen) | Vynásobí zelenou komponentu hodnotou parametru. |
| [SetBlue](#SetBlue) | Změní modrou komponentu barvy na hodnotu parametru. |
| [AddBlue](#AddBlue) | Přidá hodnotu parametru k modré komponentě barvy. |
| [MultiplyBlue](#MultiplyBlue) | Vynásobí modrou komponentu hodnotou parametru. |
| [Gamma](#Gamma) | Gamma korekce. |
| [InverseGamma](#InverseGamma) | Inverzní gamma korekce. |
### Tint {#Tint}
```
public static final int Tint
```

Zesvětluje barvu. Parametr je v rozsahu mezi 0 (původní barva) a 1 (bílá).

### Shade {#Shade}
```
public static final int Shade
```

Ztmaví barvu. Parametr je v rozsahu mezi 0 (původní barva) a 1 (černá).

### Complement {#Complement}
```
public static final int Complement
```

Změní barvu na doplňkovou RGB barvu. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Změní barvu na invertovanou barvu. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Změní barvu na šedou se stejnou světlostí. Parametr je ignorován.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Definuje alfa komponentu barvy. Parametr je v rozsahu mezi 0 (transparentní) a 1 (neprůhledná).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Přidá hodnotu parametru k alfa komponentě barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Vynásobí alfa komponentu hodnotou parametru.

### SetHue {#SetHue}
```
public static final int SetHue
```

Změní komponentu odstínu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Přidá hodnotu parametru k komponentě odstínu barvy. Parametr je v rozsahu mezi -360 a 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Vynásobí komponentu odstínu hodnotou parametru.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Změní komponentu sytosti barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Přidá hodnotu parametru k komponentě sytosti barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Vynásobí komponentu sytosti hodnotou parametru.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Změní komponentu jasu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Přidá hodnotu parametru k komponentě jasu barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Vynásobí komponentu jasu hodnotou parametru.

### SetRed {#SetRed}
```
public static final int SetRed
```

Změní červenou komponentu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Přidá hodnotu parametru k červené komponentě barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Vynásobí červenou komponentu parametrem.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Změní zelenou komponentu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Přidá parametr k zelené komponentě barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Vynásobí zelenou komponentu hodnotou parametru.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Změní modrou komponentu barvy na hodnotu parametru. Parametr je v rozsahu mezi 0 a 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Přidá hodnotu parametru k modré komponentě barvy. Parametr je v rozsahu mezi -1 a 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Vynásobí modrou komponentu hodnotou parametru.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma korekce. Parametr je ignorován.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Inverzní gamma korekce. Parametr je ignorován.