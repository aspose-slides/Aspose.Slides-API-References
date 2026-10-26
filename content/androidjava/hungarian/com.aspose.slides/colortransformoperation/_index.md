---
title: ColorTransformOperation
second_title: Aspose.Slides Androidra Java API Referencián keresztül
description: Színtranszformációs műveletet definiál.
type: docs
url: /hu/com.aspose.slides/colortransformoperation/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Színtranszformációs műveletet definiál.

## Mezők

| Mező | Leírás |
| --- | --- |
| [Tint](#Tint) | Színárnyalatot ad a színhez. |
| [Shade](#Shade) | Színt sötétít. |
| [Complement](#Complement) | A színt RGB komplementer színre változtatja. |
| [Inverse](#Inverse) | A színt invertált színre változtatja. |
| [Grayscale](#Grayscale) | A színt egy azonos fényerősségű szürke színre változtatja. |
| [SetAlpha](#SetAlpha) | A szín alfa komponensét definiálja. |
| [AddAlpha](#AddAlpha) | Hozzáadja a paraméter értékét a szín alfa komponenséhez. |
| [MultiplyAlpha](#MultiplyAlpha) | Az alfa komponenst megszorozza a paraméter értékével. |
| [SetHue](#SetHue) | A szín árnyalat komponensét a paraméter értékére állítja. |
| [AddHue](#AddHue) | Hozzáadja a paraméter értékét a szín árnyalat komponenshez. |
| [MultiplyHue](#MultiplyHue) | Az árnyalat komponenst megszorozza a paraméter értékével. |
| [SetSaturation](#SetSaturation) | A szaturáció komponensét a paraméter értékére állítja. |
| [AddSaturation](#AddSaturation) | Hozzáadja a paraméter értékét a szaturáció komponenshez. |
| [MultiplySaturation](#MultiplySaturation) | A szaturáció komponenst megszorozza a paraméter értékével. |
| [SetLuminance](#SetLuminance) | A luminancia komponenst a paraméter értékére állítja. |
| [AddLuminance](#AddLuminance) | Hozzáadja a paraméter értékét a luminancia komponenshez. |
| [MultiplyLuminance](#MultiplyLuminance) | A luminancia komponenst megszorozza a paraméter értékével. |
| [SetRed](#SetRed) | A vörös komponenst a paraméter értékére állítja. |
| [AddRed](#AddRed) | Hozzáadja a paraméter értékét a vörös komponenshez. |
| [MultiplyRed](#MultiplyRed) | A vörös komponenst megszorozza a paraméterrel. |
| [SetGreen](#SetGreen) | A zöld komponenst a paraméter értékére állítja. |
| [AddGreen](#AddGreen) | Hozzáad egy paramétert a zöld komponenshez. |
| [MultiplyGreen](#MultiplyGreen) | A zöld komponenst megszorozza a paraméter értékével. |
| [SetBlue](#SetBlue) | A kék komponenst a paraméter értékére állítja. |
| [AddBlue](#AddBlue) | Hozzáadja a paraméter értékét a kék komponenshez. |
| [MultiplyBlue](#MultiplyBlue) | A kék komponenst megszorozza a paraméter értékével. |
| [Gamma](#Gamma) | Gamma korrekció. |
| [InverseGamma](#InverseGamma) | Inverz gamma korrekció. |

### Tint {#Tint}
```
public static final int Tint
```

Színárnyalatot ad a színhez. A paraméter 0 (eredeti szín) és 1 (fehér) között van.

### Shade {#Shade}
```
public static final int Shade
```

Sötétíti a színt. A paraméter 0 (eredeti szín) és 1 (fekete) között van.

### Complement {#Complement}
```
public static final int Complement
```

A színt RGB komplementer színre változtatja. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

A színt invertált színre változtatja. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

A színt egy azonos fényerősségű szürke színre változtatja. A paramétert figyelmen kívül hagyja.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

A szín alfa komponensét definiálja. A paraméter 0 (átlátszó) és 1 (átláthatatlan) között van.

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Hozzáadja a paraméter értékét a szín alfa komponenséhez. A paraméter -1 és 1 között van.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Az alfa komponenst megszorozza a paraméter értékével.

### SetHue {#SetHue}
```
public static final int SetHue
```

A szín árnyalat komponensét a paraméter értékére állítja. A paraméter 0 és 360 között van.

### AddHue {#AddHue}
```
public static final int AddHue
```

Hozzáadja a paraméter értékét a szín árnyalat komponenshez. A paraméter -360 és 360 között van.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Az árnyalat komponenst megszorozza a paraméter értékével.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

A szaturáció komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Hozzáadja a paraméter értékét a szaturáció komponenshez. A paraméter -1 és 1 között van.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

A szaturáció komponenst megszorozza a paraméter értékével.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

A luminancia komponenst a paraméter értékére állítja. A paraméter 0 és 1 között van.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Hozzáadja a paraméter értékét a luminancia komponenshez. A paraméter -1 és 1 között van.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

A luminancia komponenst megszorozza a paraméter értékével.

### SetRed {#SetRed}
```
public static final int SetRed
```

A vörös komponenst a paraméter értékére állítja. A paraméter 0 és 1 között van.

### AddRed {#AddRed}
```
public static final int AddRed
```

Hozzáadja a paraméter értékét a vörös komponenshez. A paraméter -1 és 1 között van.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

A vörös komponenst megszorozza a paraméterrel.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

A zöld komponenst a paraméter értékére állítja. A paraméter 0 és 1 között van.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Hozzáad egy paramétert a zöld komponenshez. A paraméter -1 és 1 között van.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

A zöld komponenst megszorozza a paraméter értékével.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

A kék komponenst a paraméter értékére állítja. A paraméter 0 és 360 között van.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Hozzáadja a paraméter értékét a kék komponenshez. A paraméter -1 és 1 között van.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

A kék komponenst megszorozza a paraméter értékével.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma korrekció. A paraméter figyelmen kívül hagyott.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Inverz gamma korrekció. A paraméter figyelmen kívül hagyott.