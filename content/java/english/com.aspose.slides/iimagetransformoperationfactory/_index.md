---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create image effects instances
type: docs
url: /com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Allows to create image effects' instances

--------------------

For COM interface.
## Methods

| Method | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Creates Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Creates Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Creates Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Creates Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Creates Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Creates Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Creates Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Creates BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Creates Blur effect. |
| [createColorChange()](#createColorChange--) | Creates Color change effect. |
| [createColorReplace()](#createColorReplace--) | Creates Color replace effect. |
| [createDuotone()](#createDuotone--) | Creates Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Creates Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Creates Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Creates Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Createtes Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Creates Tint effect. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Creates Alpha BiLevel effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Creates Alpha Ceiling effect.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Creates Alpha floor effect.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Creates Alpha inverse effect.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Creates Alpha modulate effect.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Creates Alpha modulate fixed effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Amount. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Creates Alpha replace effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


Creates BiLevel effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Creates Blur effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Creates Color change effect.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Creates Color replace effect.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Creates Duotone effect.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Creates Fill overlay effect.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Creates Gray scale effect.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Creates Hue Saturation Luminance effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Createtes Luminance effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Creates Tint effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Tint effect.
