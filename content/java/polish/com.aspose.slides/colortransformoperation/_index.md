---
title: ColorTransformOperation
second_title: Aspose.Slides dla Java – referencja API
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
| [Shade](#Shade) | Przysłania kolor. |
| [Complement](#Complement) | Zmienia kolor na RGB komplementarny. |
| [Inverse](#Inverse) | Zmienia kolor na odwrócony. |
| [Grayscale](#Grayscale) | Zmienia kolor na szary przy tej samej jasności. |
| [SetAlpha](#SetAlpha) | Definiuje składnik alfa koloru. |
| [AddAlpha](#AddAlpha) | Dodaje wartość parametru do składnika alfa koloru. |
| [MultiplyAlpha](#MultiplyAlpha) | Mnoży składnik alfa przez wartość parametru. |
| [SetHue](#SetHue) | Zmienia składnik barwy (hue) koloru na wartość parametru. |
| [AddHue](#AddHue) | Dodaje wartość parametru do składnika barwy koloru. |
| [MultiplyHue](#MultiplyHue) | Mnoży składnik barwy koloru przez wartość parametru. |
| [SetSaturation](#SetSaturation) | Zmienia składnik nasycenia koloru na wartość parametru. |
| [AddSaturation](#AddSaturation) | Dodaje wartość parametru do składnika nasycenia koloru. |
| [MultiplySaturation](#MultiplySaturation) | Mnoży składnik nasycenia koloru przez wartość parametru. |
| [SetLuminance](#SetLuminance) | Zmienia składnik luminancji koloru na wartość parametru. |
| [AddLuminance](#AddLuminance) | Dodaje wartość parametru do składnika luminancji koloru. |
| [MultiplyLuminance](#MultiplyLuminance) | Mnoży składnik luminancji koloru przez wartość parametru. |
| [SetRed](#SetRed) | Zmienia składnik czerwonego (red) koloru na wartość parametru. |
| [AddRed](#AddRed) | Dodaje wartość parametru do składnika czerwonego koloru. |
| [MultiplyRed](#MultiplyRed) | Mnoży składnik czerwonego koloru przez parametr. |
| [SetGreen](#SetGreen) | Zmienia składnik zielonego (green) koloru na wartość parametru. |
| [AddGreen](#AddGreen) | Dodaje parametr do składnika zielonego koloru. |
| [MultiplyGreen](#MultiplyGreen) | Mnoży składnik zielonego koloru przez wartość parametru. |
| [SetBlue](#SetBlue) | Zmienia składnik niebieskiego (blue) koloru na wartość parametru. |
| [AddBlue](#AddBlue) | Dodaje wartość parametru do składnika niebieskiego koloru. |
| [MultiplyBlue](#MultiplyBlue) | Mnoży składnik niebieskiego koloru przez wartość parametru. |
| [Gamma](#Gamma) | Korekcja gamma. |
| [InverseGamma](#InverseGamma) | Odwrócona korekcja gamma. |
### Tint {#Tint}
```
public static final int Tint
```


Tonuje kolor. Parametr znajduje się w przedziale od 0 (oryginalny kolor) do 1 (biały).

### Shade {#Shade}
```
public static final int Shade
```


Przysłania kolor. Parametr znajduje się w przedziale od 0 (oryginalny kolor) do 1 (czarny).

### Complement {#Complement}
```
public static final int Complement
```


Zmienia kolor na RGB komplementarny. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```


Zmienia kolor na odwrócony. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Zmienia kolor na szary przy tej samej jasności. Parametr jest ignorowany.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```


Definiuje składnik alfa koloru. Parametr znajduje się w przedziale od 0 (przezroczysty) do 1 (nieprzezroczysty).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```


Dodaje wartość parametru do składnika alfa koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```


Mnoży składnik alfa przez wartość parametru.

### SetHue {#SetHue}
```
public static final int SetHue
```


Zmienia składnik barwy (hue) koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 360.

### AddHue {#AddHue}
```
public static final int AddHue
```


Dodaje wartość parametru do składnika barwy koloru. Parametr znajduje się w przedziale od -360 do 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```


Mnoży składnik barwy koloru przez wartość parametru.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```


Zmienia składnik nasycenia koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```


Dodaje wartość parametru do składnika nasycenia koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```


Mnoży składnik nasycenia koloru przez wartość parametru.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```


Zmienia składnik luminancji koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```


Dodaje wartość parametru do składnika luminancji koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```


Mnoży składnik luminancji koloru przez wartość parametru.

### SetRed {#SetRed}
```
public static final int SetRed
```


Zmienia składnik czerwonego (red) koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1.

### AddRed {#AddRed}
```
public static final int AddRed
```


Dodaje wartość parametru do składnika czerwonego koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```


Mnoży składnik czerwonego koloru przez parametr.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```


Zmienia składnik zielonego (green) koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```


Dodaje parametr do składnika zielonego koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```


Mnoży składnik zielonego koloru przez wartość parametru.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```


Zmienia składnik niebieskiego (blue) koloru na wartość parametru. Parametr znajduje się w przedziale od 0 do 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```


Dodaje wartość parametru do składnika niebieskiego koloru. Parametr znajduje się w przedziale od -1 do 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```


Mnoży składnik niebieskiego koloru przez wartość parametru.

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