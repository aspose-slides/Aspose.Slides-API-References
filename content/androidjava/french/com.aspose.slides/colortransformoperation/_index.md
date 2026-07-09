---
title: ColorTransformOperation
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Définit l'opération de transformation de couleur.
type: docs
url: /fr/com.aspose.slides/colortransformoperation/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Définit l'opération de transformation de couleur.
## Champs

| Champ | Description |
| --- | --- |
| [Tint](#Tint) | Teinte la couleur. |
| [Shade](#Shade) | Assombrit la couleur. |
| [Complement](#Complement) | Change la couleur en une couleur complémentaire RGB. |
| [Inverse](#Inverse) | Change la couleur en couleur inversée. |
| [Grayscale](#Grayscale) | Convertit la couleur en gris avec la même luminosité. |
| [SetAlpha](#SetAlpha) | Définit un composant alpha de la couleur. |
| [AddAlpha](#AddAlpha) | Ajoute la valeur d'un paramètre à un composant alpha de la couleur. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplie un composant alpha par la valeur d'un paramètre. |
| [SetHue](#SetHue) | Change le composant teinte de la couleur à la valeur d'un paramètre. |
| [AddHue](#AddHue) | Ajoute la valeur du paramètre au composant teinte de la couleur. |
| [MultiplyHue](#MultiplyHue) | Multiplie le composant teinte par la valeur d'un paramètre. |
| [SetSaturation](#SetSaturation) | Change le composant saturation de la couleur à la valeur d'un paramètre. |
| [AddSaturation](#AddSaturation) | Ajoute la valeur du paramètre au composant saturation de la couleur. |
| [MultiplySaturation](#MultiplySaturation) | Multiplie le composant saturation par la valeur d'un paramètre. |
| [SetLuminance](#SetLuminance) | Change le composant luminance de la couleur à la valeur d'un paramètre. |
| [AddLuminance](#AddLuminance) | Ajoute la valeur du paramètre au composant luminance de la couleur. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplie le composant luminance par la valeur d'un paramètre. |
| [SetRed](#SetRed) | Change le composant rouge de la couleur à la valeur d'un paramètre. |
| [AddRed](#AddRed) | Ajoute la valeur du paramètre au composant rouge de la couleur. |
| [MultiplyRed](#MultiplyRed) | Multiplie le composant rouge par un paramètre. |
| [SetGreen](#SetGreen) | Change le composant vert de la couleur à la valeur d'un paramètre. |
| [AddGreen](#AddGreen) | Ajoute un paramètre au composant vert de la couleur. |
| [MultiplyGreen](#MultiplyGreen) | Multiplie le composant vert par la valeur d'un paramètre. |
| [SetBlue](#SetBlue) | Change le composant bleu de la couleur à la valeur d'un paramètre. |
| [AddBlue](#AddBlue) | Ajoute la valeur du paramètre au composant bleu de la couleur. |
| [MultiplyBlue](#MultiplyBlue) | Multiplie le composant bleu par la valeur d'un paramètre. |
| [Gamma](#Gamma) | Correction gamma. |
| [InverseGamma](#InverseGamma) | Correction gamma inverse. |
### Tint {#Tint}
```
public static final int Tint
```

Teinte la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (blanc).

### Shade {#Shade}
```
public static final int Shade
```

Assombrit la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (noir).

### Complement {#Complement}
```
public static final int Complement
```

Change la couleur en une couleur complémentaire RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Change la couleur en couleur inversée. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Convertit la couleur en gris avec la même luminosité. Paramètre ignoré.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Définit un composant alpha de la couleur. Le paramètre est compris entre 0 (transparent) et 1 (opaque).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Ajoute la valeur d'un paramètre à un composant alpha de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multiplie un composant alpha par la valeur d'un paramètre.

### SetHue {#SetHue}
```
public static final int SetHue
```

Change le composant teinte de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Ajoute la valeur du paramètre au composant teinte de la couleur. Le paramètre est compris entre -360 et 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multiplie le composant teinte par la valeur d'un paramètre.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Change le composant saturation de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Ajoute la valeur du paramètre au composant saturation de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multiplie le composant saturation par la valeur d'un paramètre.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Change le composant luminance de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Ajoute la valeur du paramètre au composant luminance de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multiplie le composant luminance par la valeur d'un paramètre.

### SetRed {#SetRed}
```
public static final int SetRed
```

Change le composant rouge de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Ajoute la valeur du paramètre au composant rouge de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multiplie le composant rouge par un paramètre.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Change le composant vert de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Ajoute un paramètre au composant vert de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multiplie le composant vert par la valeur d'un paramètre.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Change le composant bleu de la couleur à la valeur d'un paramètre. Le paramètre est compris entre 0 et 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Ajoute la valeur du paramètre au composant bleu de la couleur. Le paramètre est compris entre -1 et 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multiplie le composant bleu par la valeur d'un paramètre.

### Gamma {#Gamma}
```
public static final int Gamma
```

Correction gamma. Paramètre ignoré.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Correction gamma inverse. Paramètre ignoré.