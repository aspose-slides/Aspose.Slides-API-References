---
title: ColorTransformOperation
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Definiuje operację transformacji koloru.
type: docs
url: /pl/com.aspose.slides/colortransformoperation/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definiuje operację transformacji koloru.
## Pola

| Pole | Opis |
| --- | --- |
| [Tint](#Tint) | Tonuje kolor. |
| [Shade](#Shade) | Cieniowanie koloru. |
| [Complement](#Complement) | Zmienia kolor na uzupełniający w RGB. |
| [Inverse](#Inverse) | Zmienia kolor na odwrócony kolor. |
| [Grayscale](#Grayscale) | Zmienia kolor na szary o tej samej jasności. |
| [SetAlpha](#SetAlpha) | Definiuje komponent alfa koloru. |
| [AddAlpha](#AddAlpha) | Dodaje wartość parametru do komponentu alfa koloru. |
| [MultiplyAlpha](#MultiplyAlpha) | Mnoży komponent alfa przez wartość parametru. |
| [SetHue](#SetHue) | Zmienia komponent odcienia koloru na wartość parametru. |
| [AddHue](#AddHue) | Dodaje wartość parametru do komponentu odcienia koloru. |
| [MultiplyHue](#MultiplyHue) | Mnoży komponent odcienia przez wartość parametru. |
| [SetSaturation](#SetSaturation) | Zmienia komponent nasycenia koloru na wartość parametru. |
| [AddSaturation](#AddSaturation) | Dodaje wartość parametru do komponentu nasycenia koloru. |
| [MultiplySaturation](#MultiplySaturation) | Mnoży komponent nasycenia przez wartość parametru. |
| [SetLuminance](#SetLuminance) | Zmienia komponent luminancji koloru na wartość parametru. |
| [AddLuminance](#AddLuminance) | Dodaje wartość parametru do komponentu luminancji koloru. |
| [MultiplyLuminance](#MultiplyLuminance) | Mnoży komponent luminancji przez wartość parametru. |
| [SetRed](#SetRed) | Zmienia czerwony komponent koloru na wartość parametru. |
| [AddRed](#AddRed) | Dodaje wartość parametru do czerwonego komponentu koloru. |
| [MultiplyRed](#MultiplyRed) | Mnoży czerwony komponent przez parametr. |
| [SetGreen](#SetGreen) | Zmienia zielony komponent koloru na wartość parametru. |
| [AddGreen](#AddGreen) | Dodaje parametr do zielonego komponentu koloru. |
| [MultiplyGreen](#MultiplyGreen) | Mnoży zielony komponent koloru przez wartość parametru. |
| [SetBlue](#SetBlue) | Zmienia niebieski komponent koloru na wartość parametru. |
| [AddBlue](#AddBlue) | Dodaje wartość parametru do niebieskiego komponentu koloru. |
| [MultiplyBlue](#MultiplyBlue) | Mnoży niebieski komponent koloru przez wartość parametru. |
| [Gamma](#Gamma) | Korekcja gamma. |
| [InverseGamma](#InverseGamma) | Odwrócona korekcja gamma. |
### Tint {#Tint}
```
public static final int Tint
```

Tonuje kolor. Parametr mieści się w zakresie od 0 (pierwotny kolor) do 1 (biały).

### Shade {#Shade}
```
public static final int Shade
```

Cieniowanie koloru. Parametr mieści się w zakresie od 0 (pierwotny kolor) do 1 (czarny).

### Complement {#Complement}
```
public static final int Complement
```

Zmienia kolor na uzupełniający w RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Zmienia kolor na odwrócony kolor. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Zmienia kolor na szary o tej samej jasności. Parametr jest ignorowany.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Definiuje komponent alfa koloru. Parametr mieści się w zakresie od 0 (przezroczysty) do 1 (nieprzezroczysty).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Dodaje wartość parametru do komponentu alfa koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Mnoży komponent alfa przez wartość parametru.

### SetHue {#SetHue}
```
public static final int SetHue
```

Zmienia komponent odcienia koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Dodaje wartość parametru do komponentu odcienia koloru. Parametr mieści się w zakresie od -360 do 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Mnoży komponent odcienia przez wartość parametru.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Zmienia komponent nasycenia koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Dodaje wartość parametru do komponentu nasycenia koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Mnoży komponent nasycenia przez wartość parametru.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Zmienia komponent luminancji koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Dodaje wartość parametru do komponentu luminancji koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Mnoży komponent luminancji przez wartość parametru.

### SetRed {#SetRed}
```
public static final int SetRed
```

Zmienia czerwony komponent koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Dodaje wartość parametru do czerwonego komponentu koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Mnoży czerwony komponent przez parametr.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Zmienia zielony komponent koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Dodaje parametr do zielonego komponentu koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Mnoży zielony komponent koloru przez wartość parametru.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Zmienia niebieski komponent koloru na wartość parametru. Parametr mieści się w zakresie od 0 do 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Dodaje wartość parametru do niebieskiego komponentu koloru. Parametr mieści się w zakresie od -1 do 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Mnoży niebieski komponent koloru przez wartość parametru.

### Gamma {#Gamma}
```
public static final int Gamma
```

Korekcja gamma. Parametr jest ignorowany.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Odwrócona korekcja gamma. Parametr jest ignorowany.