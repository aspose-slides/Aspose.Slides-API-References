---
title: ColorTransformOperation
second_title: Aspose.Slides Java API referencia
description: Színtranszformációs műveletet definiál.
type: docs
url: /hu/com.aspose.slides/colortransformoperation/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

A színtransformációs műveletet definiálja.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Tint](#Tint) | Megvilágítja a színt. |
| [Shade](#Shade) | Sötétíti a színt. |
| [Complement](#Complement) | A színt RGB komplementer színre változtatja. |
| [Inverse](#Inverse) | A színt invertált színre változtatja. |
| [Grayscale](#Grayscale) | A színt ugyanazzal a fényerővel szürke színre változtatja. |
| [SetAlpha](#SetAlpha) | Az alfa komponensét definiálja a színnek. |
| [AddAlpha](#AddAlpha) | A paraméter értékét hozzáadja a szín alfa komponenséhez. |
| [MultiplyAlpha](#MultiplyAlpha) | Az alfa komponenst szorozza a paraméter értékével. |
| [SetHue](#SetHue) | A szín árnyalat komponensét a paraméter értékére állítja. |
| [AddHue](#AddHue) | A paraméter értékét hozzáadja a szín árnyalat komponenséhez. |
| [MultiplyHue](#MultiplyHue) | Az árnyalat komponenst a paraméter értékével szorozza. |
| [SetSaturation](#SetSaturation) | A szaturáció komponensét a paraméter értékére állítja. |
| [AddSaturation](#AddSaturation) | A paraméter értékét hozzáadja a szaturáció komponenshez. |
| [MultiplySaturation](#MultiplySaturation) | A szaturáció komponenst a paraméter értékével szorozza. |
| [SetLuminance](#SetLuminance) | A luminancia komponensét a paraméter értékére állítja. |
| [AddLuminance](#AddLuminance) | A paraméter értékét hozzáadja a luminancia komponenshez. |
| [MultiplyLuminance](#MultiplyLuminance) | A luminancia komponenst a paraméter értékével szorozza. |
| [SetRed](#SetRed) | A piros komponensét a paraméter értékére állítja. |
| [AddRed](#AddRed) | A paraméter értékét hozzáadja a piros komponenshez. |
| [MultiplyRed](#MultiplyRed) | A piros komponenst a paraméterrel szorozza. |
| [SetGreen](#SetGreen) | A zöld komponensét a paraméter értékére állítja. |
| [AddGreen](#AddGreen) | A paramétert hozzáadja a zöld komponenshez. |
| [MultiplyGreen](#MultiplyGreen) | A zöld komponenst a paraméter értékével szorozza. |
| [SetBlue](#SetBlue) | A kék komponensét a paraméter értékére állítja. |
| [AddBlue](#AddBlue) | A paraméter értékét hozzáadja a kék komponenshez. |
| [MultiplyBlue](#MultiplyBlue) | A kék komponenst a paraméter értékével szorozza. |
| [Gamma](#Gamma) | Gamma korrekció. |
| [InverseGamma](#InverseGamma) | Inverz gamma korrekció. |
### Tint {#Tint}
```
public static final int Tint
```

Megvilágítja a színt. A paraméter értéke 0 és 1 között van (0 = eredeti szín, 1 = fehér).

### Shade {#Shade}
```
public static final int Shade
```

Sötétíti a színt. A paraméter értéke 0 és 1 között van (0 = eredeti szín, 1 = fekete).

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

A színt ugyanazzal a fényerővel szürke színre változtatja. A paramétert figyelmen kívül hagyja.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Az alfa komponensét definiálja a színnek. A paraméter értéke 0 és 1 között van (0 = átlátszó, 1 = átlátszatlan).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

A paraméter értékét hozzáadja a szín alfa komponenséhez. A paraméter értéke -1 és 1 között van.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Az alfa komponenst szorozza a paraméter értékével.

### SetHue {#SetHue}
```
public static final int SetHue
```

A szín árnyalat komponensét a paraméter értékére állítja. A paraméter értéke 0 és 360 között van.

### AddHue {#AddHue}
```
public static final int AddHue
```

A paraméter értékét hozzáadja a szín árnyalat komponenséhez. A paraméter értéke -360 és 360 között van.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Az árnyalat komponenst a paraméter értékével szorozza.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

A szaturáció komponensét a paraméter értékére állítja. A paraméter értéke 0 és 1 között van.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

A paraméter értékét hozzáadja a szaturáció komponenshez. A paraméter értéke -1 és 1 között van.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

A szaturáció komponenst a paraméter értékével szorozza.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

A luminancia komponensét a paraméter értékére állítja. A paraméter értéke 0 és 1 között van.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

A paraméter értékét hozzáadja a luminancia komponenshez. A paraméter értéke -1 és 1 között van.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

A luminancia komponenst a paraméter értékével szorozza.

### SetRed {#SetRed}
```
public static final int SetRed
```

A piros komponensét a paraméter értékére állítja. A paraméter értéke 0 és 1 között van.

### AddRed {#AddRed}
```
public static final int AddRed
```

A paraméter értékét hozzáadja a piros komponenshez. A paraméter értéke -1 és 1 között van.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

A piros komponenst a paraméterrel szorozza.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

A zöld komponensét a paraméter értékére állítja. A paraméter értéke 0 és 1 között van.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

A paramétert hozzáadja a zöld komponenshez. A paraméter értéke -1 és 1 között van.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

A zöld komponenst a paraméter értékével szorozza.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

A kék komponensét a paraméter értékére állítja. A paraméter értéke 0 és 360 között van.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

A paraméter értékét hozzáadja a kék komponenshez. A paraméter értéke -1 és 1 között van.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

A kék komponenst a paraméter értékével szorozza.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma korrekció. A paramétert figyelmen kívül hagyja.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Inverz gamma korrekció. A paramétert figyelmen kívül hagyja.