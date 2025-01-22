---
title: ColorTransformOperation
second_title: Aspose.Slides for C++ API Reference
description: Defines color transform operation.
type: docs
weight: 5643
url: /aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum


Defines color transform operation.

```cpp
enum class ColorTransformOperation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Tint | 0 | Tints the color. Parameter is in range between 0 (original color) and 1 (white). |
| Shade | 1 | Shades the color. Parameter is in range between 0 (original color) and 1 (black). |
| Complement | 2 | Changes the color to a RGB complementary one. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Changes the color to an inverted color. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Changes the color to a gray one with same lightness. Parameter ignored. |
| SetAlpha | 5 | Defines an alpha component of the color. Parameter is in range between 0 (transparent) and 1 (opaque). |
| AddAlpha | 6 | Adds a parameter's value to an alpha component of the color. Parameter is in range between -1 and 1. |
| MultiplyAlpha | 7 | Multiplies an alpha component to a parameter's value. |
| SetHue | 8 | Changes a hue component of the color to a parameter's value. Parameter is in range between 0 and 360. |
| AddHue | 9 | Adds parameter's value to hue component of the color. Parameter is in range between -360 and 360. |
| MultiplyHue | 10 | Multiplies a hue component to a parameter's value. |
| SetSaturation | 11 | Changes a saturation component of the color to a parameter's value. Parameter is in range between 0 and 1. |
| AddSaturation | 12 | Adds a parameter's value to a saturation component of the color. Parameter is in range between -1 and 1. |
| MultiplySaturation | 13 | Multiplies a saturation component to a parameter's value. |
| SetLuminance | 14 | Changes a luminance component of the color to a parameter's value. Parameter is in range between 0 and 1. |
| AddLuminance | 15 | Adds a parameter's value to a luminance component of the color. Parameter is in range between -1 and 1. |
| MultiplyLuminance | 16 | Multiplies a luminance component to a parameter's value. |
| SetRed | 17 | Changes a red component of the color to a parameter's value. Parameter is in range between 0 and 1. |
| AddRed | 18 | Adds a parameter's value to a red component of the color. Parameter is in range between -1 and 1. |
| MultiplyRed | 19 | Multiplies a red component to a parameter. |
| SetGreen | 20 | Changes a green component of the color to a parameter's value value. Parameter is in range between 0 and 1. |
| AddGreen | 21 | Adds a parameter to a green component of the color. Parameter is in range between -1 and 1. |
| MultiplyGreen | 22 | Multiplies a green component of the color to a parameter's value. |
| SetBlue | 23 | Changes a blue component of the color to a parameter's value. Parameter is in range between 0 and 360. |
| AddBlue | 24 | Adds a parameter's value to a blue component of the color. Parameter is in range between -1 and 1. |
| MultiplyBlue | 25 | Multiplies a blue component of the color to a parameter's value. |
| Gamma | 26 | Gamma correction. Parameter ignored. |
| InverseGamma | 27 | Inverse gamma correction. Parameter ignored. |

## See Also

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)