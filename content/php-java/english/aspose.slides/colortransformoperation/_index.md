---
title: ColorTransformOperation
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/colortransformoperation/
---

## ColorTransformOperation class

 Defines color transform operation.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[Tint](#Tint) | 0 | Tints the color. Parameter is in range between 0 (original color) and 1 (white). |
[Shade](#Shade) | 1 | Shades the color. Parameter is in range between 0 (original color) and 1 (black). |
[Complement](#Complement) | 2 | Changes the color to a RGB complementary one. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
[Inverse](#Inverse) | 3 | Changes the color to an inverted color. r = 1 - r; g = 1 - g; b = 1 - b; |
[Grayscale](#Grayscale) | 4 | Changes the color to a gray one with same lightness. Parameter ignored. |
[SetAlpha](#SetAlpha) | 5 | Defines an alpha component of the color. Parameter is in range between 0 (transparent) and 1 (opaque). |
[AddAlpha](#AddAlpha) | 6 | Adds a parameter's value to an alpha component of the color. Parameter is in range between -1 and 1. |
[MultiplyAlpha](#MultiplyAlpha) | 7 | Multiplies an alpha component to a parameter's value. |
[SetHue](#SetHue) | 8 | Changes a hue component of the color to a parameter's value. Parameter is in range between 0 and 360. |
[AddHue](#AddHue) | 9 | Adds parameter's value to hue component of the color. Parameter is in range between -360 and 360. |
[MultiplyHue](#MultiplyHue) | 10 | Multiplies a hue component to a parameter's value. |
[SetSaturation](#SetSaturation) | 11 | Changes a saturation component of the color to a parameter's value. Parameter is in range between 0 and 1. |
[AddSaturation](#AddSaturation) | 12 | Adds a parameter's value to a saturation component of the color. Parameter is in range between -1 and 1. |
[MultiplySaturation](#MultiplySaturation) | 13 | Multiplies a saturation component to a parameter's value. |
[SetLuminance](#SetLuminance) | 14 | Changes a luminance component of the color to a parameter's value. Parameter is in range between 0 and 1. |
[AddLuminance](#AddLuminance) | 15 | Adds a parameter's value to a luminance component of the color. Parameter is in range between -1 and 1. |
[MultiplyLuminance](#MultiplyLuminance) | 16 | Multiplies a luminance component to a parameter's value. |
[SetRed](#SetRed) | 17 | Changes a red component of the color to a parameter's value. Parameter is in range between 0 and 1. |
[AddRed](#AddRed) | 18 | Adds a parameter's value to a red component of the color. Parameter is in range between -1 and 1. |
[MultiplyRed](#MultiplyRed) | 19 | Multiplies a red component to a parameter. |
[SetGreen](#SetGreen) | 20 | Changes a green component of the color to a parameter's value value. Parameter is in range between 0 and 1. |
[AddGreen](#AddGreen) | 21 | Adds a parameter to a green component of the color. Parameter is in range between -1 and 1. |
[MultiplyGreen](#MultiplyGreen) | 22 | Multiplies a green component of the color to a parameter's value. |
[SetBlue](#SetBlue) | 23 | Changes a blue component of the color to a parameter's value. Parameter is in range between 0 and 360. |
[AddBlue](#AddBlue) | 24 | Adds a parameter's value to a blue component of the color. Parameter is in range between -1 and 1. |
[MultiplyBlue](#MultiplyBlue) | 25 | Multiplies a blue component of the color to a parameter's value. |
[Gamma](#Gamma) | 26 | Gamma correction. Parameter ignored. |
[InverseGamma](#InverseGamma) | 27 | Inverse gamma correction. Parameter ignored. |


---


### Tint {#Tint}
Tints the color. Parameter is in range between 0 (original color) and 1 (white).

---

### Shade {#Shade}
Shades the color. Parameter is in range between 0 (original color) and 1 (black).

---

### Complement {#Complement}
Changes the color to a RGB complementary one. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

---

### Inverse {#Inverse}
Changes the color to an inverted color. r = 1 - r; g = 1 - g; b = 1 - b;

---

### Grayscale {#Grayscale}
Changes the color to a gray one with same lightness. Parameter ignored.

---

### SetAlpha {#SetAlpha}
Defines an alpha component of the color. Parameter is in range between 0 (transparent) and 1 (opaque).

---

### AddAlpha {#AddAlpha}
Adds a parameter's value to an alpha component of the color. Parameter is in range between -1 and 1.

---

### MultiplyAlpha {#MultiplyAlpha}
Multiplies an alpha component to a parameter's value.

---

### SetHue {#SetHue}
Changes a hue component of the color to a parameter's value. Parameter is in range between 0 and 360.

---

### AddHue {#AddHue}
Adds parameter's value to hue component of the color. Parameter is in range between -360 and 360.

---

### MultiplyHue {#MultiplyHue}
Multiplies a hue component to a parameter's value.

---

### SetSaturation {#SetSaturation}
Changes a saturation component of the color to a parameter's value. Parameter is in range between 0 and 1.

---

### AddSaturation {#AddSaturation}
Adds a parameter's value to a saturation component of the color. Parameter is in range between -1 and 1.

---

### MultiplySaturation {#MultiplySaturation}
Multiplies a saturation component to a parameter's value.

---

### SetLuminance {#SetLuminance}
Changes a luminance component of the color to a parameter's value. Parameter is in range between 0 and 1.

---

### AddLuminance {#AddLuminance}
Adds a parameter's value to a luminance component of the color. Parameter is in range between -1 and 1.

---

### MultiplyLuminance {#MultiplyLuminance}
Multiplies a luminance component to a parameter's value.

---

### SetRed {#SetRed}
Changes a red component of the color to a parameter's value. Parameter is in range between 0 and 1.

---

### AddRed {#AddRed}
Adds a parameter's value to a red component of the color. Parameter is in range between -1 and 1.

---

### MultiplyRed {#MultiplyRed}
Multiplies a red component to a parameter.

---

### SetGreen {#SetGreen}
Changes a green component of the color to a parameter's value value. Parameter is in range between 0 and 1.

---

### AddGreen {#AddGreen}
Adds a parameter to a green component of the color. Parameter is in range between -1 and 1.

---

### MultiplyGreen {#MultiplyGreen}
Multiplies a green component of the color to a parameter's value.

---

### SetBlue {#SetBlue}
Changes a blue component of the color to a parameter's value. Parameter is in range between 0 and 360.

---

### AddBlue {#AddBlue}
Adds a parameter's value to a blue component of the color. Parameter is in range between -1 and 1.

---

### MultiplyBlue {#MultiplyBlue}
Multiplies a blue component of the color to a parameter's value.

---

### Gamma {#Gamma}
Gamma correction. Parameter ignored.

---

### InverseGamma {#InverseGamma}
Inverse gamma correction. Parameter ignored.

---


