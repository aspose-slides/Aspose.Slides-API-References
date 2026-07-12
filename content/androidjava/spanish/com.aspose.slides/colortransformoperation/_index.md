---
title: ColorTransformOperation
second_title: Referencia de la API de Aspose.Slides para Android vía Java
description: Define la operación de transformación de color.
type: docs
url: /es/com.aspose.slides/colortransformoperation/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Define la operación de transformación de color.
## Campos

| Campo | Descripción |
| --- | --- |
| [Tint](#Tint) | Tiñe el color. |
| [Shade](#Shade) | Oscurece el color. |
| [Complement](#Complement) | Cambia el color a uno complementario RGB. |
| [Inverse](#Inverse) | Cambia el color a un color invertido. |
| [Grayscale](#Grayscale) | Cambia el color a un gris con la misma luminosidad. |
| [SetAlpha](#SetAlpha) | Define un componente alfa del color. |
| [AddAlpha](#AddAlpha) | Añade el valor de un parámetro a un componente alfa del color. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplica un componente alfa por el valor de un parámetro. |
| [SetHue](#SetHue) | Cambia el componente de tono del color al valor de un parámetro. |
| [AddHue](#AddHue) | Añade el valor de un parámetro al componente de tono del color. |
| [MultiplyHue](#MultiplyHue) | Multiplica un componente de tono por el valor de un parámetro. |
| [SetSaturation](#SetSaturation) | Cambia el componente de saturación del color al valor de un parámetro. |
| [AddSaturation](#AddSaturation) | Añade el valor de un parámetro al componente de saturación del color. |
| [MultiplySaturation](#MultiplySaturation) | Multiplica un componente de saturación por el valor de un parámetro. |
| [SetLuminance](#SetLuminance) | Cambia el componente de luminancia del color al valor de un parámetro. |
| [AddLuminance](#AddLuminance) | Añade el valor de un parámetro al componente de luminancia del color. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplica un componente de luminancia por el valor de un parámetro. |
| [SetRed](#SetRed) | Cambia el componente rojo del color al valor de un parámetro. |
| [AddRed](#AddRed) | Añade el valor de un parámetro al componente rojo del color. |
| [MultiplyRed](#MultiplyRed) | Multiplica un componente rojo por un parámetro. |
| [SetGreen](#SetGreen) | Cambia el componente verde del color al valor del parámetro. |
| [AddGreen](#AddGreen) | Añade un parámetro al componente verde del color. |
| [MultiplyGreen](#MultiplyGreen) | Multiplica un componente verde por el valor de un parámetro. |
| [SetBlue](#SetBlue) | Cambia el componente azul del color al valor de un parámetro. |
| [AddBlue](#AddBlue) | Añade el valor de un parámetro al componente azul del color. |
| [MultiplyBlue](#MultiplyBlue) | Multiplica un componente azul por el valor de un parámetro. |
| [Gamma](#Gamma) | Corrección gamma. |
| [InverseGamma](#InverseGamma) | Corrección gamma inversa. |
### Tint {#Tint}
```
public static final int Tint
```

Tiñe el color. El parámetro está en el rango entre 0 (color original) y 1 (blanco).

### Shade {#Shade}
```
public static final int Shade
```

Oscurece el color. El parámetro está en el rango entre 0 (color original) y 1 (negro).

### Complement {#Complement}
```
public static final int Complement
```

Cambia el color a uno complementario RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Cambia el color a un color invertido. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Cambia el color a un gris con la misma luminosidad. Parámetro ignorado.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Define un componente alfa del color. El parámetro está en el rango entre 0 (transparente) y 1 (opaco).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Añade el valor de un parámetro a un componente alfa del color. El parámetro está en el rango entre -1 y 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multiplica un componente alfa por el valor de un parámetro.

### SetHue {#SetHue}
```
public static final int SetHue
```

Cambia el componente de tono del color al valor de un parámetro. El parámetro está en el rango entre 0 y 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Añade el valor de un parámetro al componente de tono del color. El parámetro está en el rango entre -360 y 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multiplica un componente de tono por el valor de un parámetro.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Cambia el componente de saturación del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Añade el valor de un parámetro al componente de saturación del color. El parámetro está en el rango entre -1 y 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multiplica un componente de saturación por el valor de un parámetro.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Cambia el componente de luminancia del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Añade el valor de un parámetro al componente de luminancia del color. El parámetro está en el rango entre -1 y 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multiplica un componente de luminancia por el valor de un parámetro.

### SetRed {#SetRed}
```
public static final int SetRed
```

Cambia el componente rojo del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Añade el valor de un parámetro al componente rojo del color. El parámetro está en el rango entre -1 y 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multiplica un componente rojo por un parámetro.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Cambia el componente verde del color al valor del parámetro. El parámetro está en el rango entre 0 y 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Añade un parámetro al componente verde del color. El parámetro está en el rango entre -1 y 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multiplica un componente verde por el valor de un parámetro.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Cambia el componente azul del color al valor de un parámetro. El parámetro está en el rango entre 0 y 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Añade el valor de un parámetro al componente azul del color. El parámetro está en el rango entre -1 y 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multiplica un componente azul por el valor de un parámetro.

### Gamma {#Gamma}
```
public static final int Gamma
```

Corrección gamma. Parámetro ignorado.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Corrección gamma inversa. Parámetro ignorado.