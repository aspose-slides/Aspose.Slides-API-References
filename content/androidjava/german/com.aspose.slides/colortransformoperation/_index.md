---
title: ColorTransformOperation
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Definiert die Farbtransformationsoperation.
type: docs
url: /de/com.aspose.slides/colortransformoperation/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definiert Farbtransformationsoperation.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Tint](#Tint) | Färbt die Farbe. |
| [Shade](#Shade) | Verdunkelt die Farbe. |
| [Complement](#Complement) | Ändert die Farbe in ein RGB-komplementäres. |
| [Inverse](#Inverse) | Ändert die Farbe in eine invertierte Farbe. |
| [Grayscale](#Grayscale) | Ändert die Farbe in ein graues mit gleicher Helligkeit. |
| [SetAlpha](#SetAlpha) | Definiert eine Alpha-Komponente der Farbe. |
| [AddAlpha](#AddAlpha) | Addiert den Wert eines Parameters zur Alpha-Komponente der Farbe. |
| [MultiplyAlpha](#MultiplyAlpha) | Multipliziert eine Alpha-Komponente mit dem Wert eines Parameters. |
| [SetHue](#SetHue) | Ändert die Farbtonkomponente der Farbe auf den Wert eines Parameters. |
| [AddHue](#AddHue) | Addiert den Wert eines Parameters zur Farbtonkomponente der Farbe. |
| [MultiplyHue](#MultiplyHue) | Multipliziert die Farbtonkomponente mit dem Wert eines Parameters. |
| [SetSaturation](#SetSaturation) | Ändert die Sättigungskomponente der Farbe auf den Wert eines Parameters. |
| [AddSaturation](#AddSaturation) | Addiert den Wert eines Parameters zur Sättigungskomponente der Farbe. |
| [MultiplySaturation](#MultiplySaturation) | Multipliziert die Sättigungskomponente mit dem Wert eines Parameters. |
| [SetLuminance](#SetLuminance) | Ändert die Luminanzkomponente der Farbe auf den Wert eines Parameters. |
| [AddLuminance](#AddLuminance) | Addiert den Wert eines Parameters zur Luminanzkomponente der Farbe. |
| [MultiplyLuminance](#MultiplyLuminance) | Multipliziert die Luminanzkomponente mit dem Wert eines Parameters. |
| [SetRed](#SetRed) | Ändert die Rotkomponente der Farbe auf den Wert eines Parameters. |
| [AddRed](#AddRed) | Addiert den Wert eines Parameters zur Rotkomponente der Farbe. |
| [MultiplyRed](#MultiplyRed) | Multipliziert die Rotkomponente mit einem Parameter. |
| [SetGreen](#SetGreen) | Ändert die Grünkomponente der Farbe auf den Wert eines Parameters. |
| [AddGreen](#AddGreen) | Addiert einen Parameter zur Grünkomponente der Farbe. |
| [MultiplyGreen](#MultiplyGreen) | Multipliziert die Grünkomponente mit dem Wert eines Parameters. |
| [SetBlue](#SetBlue) | Ändert die Blaukomponente der Farbe auf den Wert eines Parameters. |
| [AddBlue](#AddBlue) | Addiert den Wert eines Parameters zur Blaukomponente der Farbe. |
| [MultiplyBlue](#MultiplyBlue) | Multipliziert die Blaukomponente mit dem Wert eines Parameters. |
| [Gamma](#Gamma) | Gammakorrektur. |
| [InverseGamma](#InverseGamma) | Inverse Gammakorrektur. |
### Tint {#Tint}
```
public static final int Tint
```

Färbt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Weiß).

### Shade {#Shade}
```
public static final int Shade
```

Verdunkelt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Schwarz).

### Complement {#Complement}
```
public static final int Complement
```

Ändert die Farbe in ein RGB-komplementäres. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Ändert die Farbe in eine invertierte Farbe. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Ändert die Farbe in ein Graues mit gleicher Helligkeit. Parameter wird ignoriert.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Definiert eine Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen 0 (transparent) und 1 (undurchsichtig).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Addiert den Wert eines Parameters zur Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multipliziert eine Alpha-Komponente mit dem Wert eines Parameters.

### SetHue {#SetHue}
```
public static final int SetHue
```

Ändert die Farbtonkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Addiert den Wert eines Parameters zur Farbtonkomponente der Farbe. Der Parameter liegt im Bereich zwischen -360 und 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multipliziert die Farbtonkomponente mit dem Wert eines Parameters.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Ändert die Sättigungskomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Addiert den Wert eines Parameters zur Sättigungskomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multipliziert die Sättigungskomponente mit dem Wert eines Parameters.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Ändert die Luminanzkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Addiert den Wert eines Parameters zur Luminanzkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multipliziert die Luminanzkomponente mit dem Wert eines Parameters.

### SetRed {#SetRed}
```
public static final int SetRed
```

Ändert die Rotkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Addiert den Wert eines Parameters zur Rotkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multipliziert die Rotkomponente mit einem Parameter.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Ändert die Grünkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Addiert einen Parameter zur Grünkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multipliziert die Grünkomponente mit dem Wert eines Parameters.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Ändert die Blaukomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Addiert den Wert eines Parameters zur Blaukomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multipliziert die Blaukomponente mit dem Wert eines Parameters.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gammakorrektur. Parameter wird ignoriert.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Inverse Gammakorrektur. Parameter wird ignoriert.