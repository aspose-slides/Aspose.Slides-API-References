---
title: ColorTransformOperation
second_title: Aspose.Sildes for Java API Reference
description: p
 Defines color transform operation.
type: docs
weight: 118
url: /java/com.aspose.slides/colortransformoperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Defines color transform operation.
## Fields

| Field | Description |
| --- | --- |
| [Tint](#Tint) | Tints the color. |
| [Shade](#Shade) | Shades the color. |
| [Complement](#Complement) | Changes the color to a RGB complementary one. |
| [Inverse](#Inverse) | Changes the color to an inverted color. |
| [Grayscale](#Grayscale) | Changes the color to a gray one with same lightness. |
| [SetAlpha](#SetAlpha) | Defines an alpha component of the color. |
| [AddAlpha](#AddAlpha) | Adds a parameter's value to an alpha component of the color. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplies an alpha component to a parameter's value. |
| [SetHue](#SetHue) | Changes a hue component of the color to a parameter's value. |
| [AddHue](#AddHue) | Adds parameter's value to hue component of the color. |
| [MultiplyHue](#MultiplyHue) | Multiplies a hue component to a parameter's value. |
| [SetSaturation](#SetSaturation) | Changes a saturation component of the color to a parameter's value. |
| [AddSaturation](#AddSaturation) | Adds a parameter's value to a saturation component of the color. |
| [MultiplySaturation](#MultiplySaturation) | Multiplies a saturation component to a parameter's value. |
| [SetLuminance](#SetLuminance) | Changes a luminance component of the color to a parameter's value. |
| [AddLuminance](#AddLuminance) | Adds a parameter's value to a luminance component of the color. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplies a luminance component to a parameter's value. |
| [SetRed](#SetRed) | Changes a red component of the color to a parameter's value. |
| [AddRed](#AddRed) | Adds a parameter's value to a red component of the color. |
| [MultiplyRed](#MultiplyRed) | Multiplies a red component to a parameter. |
| [SetGreen](#SetGreen) | Changes a green component of the color to a parameter's value value. |
| [AddGreen](#AddGreen) | Adds a parameter to a green component of the color. |
| [MultiplyGreen](#MultiplyGreen) | Multiplies a green component of the color to a parameter's value. |
| [SetBlue](#SetBlue) | Changes a blue component of the color to a parameter's value. |
| [AddBlue](#AddBlue) | Adds a parameter's value to a blue component of the color. |
| [MultiplyBlue](#MultiplyBlue) | Multiplies a blue component of the color to a parameter's value. |
| [Gamma](#Gamma) | Gamma correction. |
| [InverseGamma](#InverseGamma) | Inverse gamma correction. |
### Tint {#Tint}
```
public static final int Tint
```


Tints the color. Parameter is in range between 0 (original color) and 1 (white).

### Shade {#Shade}
```
public static final int Shade
```


Shades the color. Parameter is in range between 0 (original color) and 1 (black).

### Complement {#Complement}
```
public static final int Complement
```


Changes the color to a RGB complementary one. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```


Changes the color to an inverted color. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Changes the color to a gray one with same lightness. Parameter ignored.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```


Defines an alpha component of the color. Parameter is in range between 0 (transparent) and 1 (opaque).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```


Adds a parameter's value to an alpha component of the color. Parameter is in range between -1 and 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```


Multiplies an alpha component to a parameter's value.

### SetHue {#SetHue}
```
public static final int SetHue
```


Changes a hue component of the color to a parameter's value. Parameter is in range between 0 and 360.

### AddHue {#AddHue}
```
public static final int AddHue
```


Adds parameter's value to hue component of the color. Parameter is in range between -360 and 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```


Multiplies a hue component to a parameter's value.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```


Changes a saturation component of the color to a parameter's value. Parameter is in range between 0 and 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```


Adds a parameter's value to a saturation component of the color. Parameter is in range between -1 and 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```


Multiplies a saturation component to a parameter's value.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```


Changes a luminance component of the color to a parameter's value. Parameter is in range between 0 and 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```


Adds a parameter's value to a luminance component of the color. Parameter is in range between -1 and 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```


Multiplies a luminance component to a parameter's value.

### SetRed {#SetRed}
```
public static final int SetRed
```


Changes a red component of the color to a parameter's value. Parameter is in range between 0 and 1.

### AddRed {#AddRed}
```
public static final int AddRed
```


Adds a parameter's value to a red component of the color. Parameter is in range between -1 and 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```


Multiplies a red component to a parameter.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```


Changes a green component of the color to a parameter's value value. Parameter is in range between 0 and 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```


Adds a parameter to a green component of the color. Parameter is in range between -1 and 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```


Multiplies a green component of the color to a parameter's value.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```


Changes a blue component of the color to a parameter's value. Parameter is in range between 0 and 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```


Adds a parameter's value to a blue component of the color. Parameter is in range between -1 and 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```


Multiplies a blue component of the color to a parameter's value.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma correction. Parameter ignored.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```


Inverse gamma correction. Parameter ignored.

