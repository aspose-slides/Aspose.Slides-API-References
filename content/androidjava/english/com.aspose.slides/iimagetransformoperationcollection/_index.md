---
title: IImageTransformOperationCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of effects apllied to an image.
type: docs
url: /com.aspose.slides/iimagetransformoperationcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Represents a collection of effects apllied to an image.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns an [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) from the collection by it's index. |
| [removeAt(int index)](#removeAt-int-) | Removes an image effect from a collection at the specified index. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Adds the new Alpha Bi-Level effect to the end of a collection. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Adds the new Alpha Ceiling effect to the end of a collection. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Adds the new Alpha Floor effect to the end of a collection. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Adds the new Alpha Inverse effect to the end of a collection. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Adds the new Alpha Modulate effect to the end of a collection. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Adds the new Alpha Modulate Fixed effect to the end of a collection. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Adds the new Alpha Replace effect to the end of a collection. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Adds the new Bi-Level (black/white) effect to the end of a collection. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Adds the new Blur effect to the end of a collection. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Adds the new Color Change effect to the end of a collection. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Adds the new Color Replacement effect to the end of a collection. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Adds the new Duotone effect to the end of a collection. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Adds the new Fill Overlay effect to the end of a collection. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Adds the new Gray Scale effect to the end of a collection. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Adds the new Hue/Saturation/Luminance effect to the end of a collection. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Adds the new Luminance effect to the end of a collection. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Adds the new Tint effect to the end of a collection. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Adds the new BrightnessContrast effect to the end of a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```


Returns an [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) from the collection by it's index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of item. |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - The [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) object.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes an image effect from a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of an image effect that should be deleted. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Adds the new Alpha Bi-Level effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | The threshold value for the alpha bi-level effect. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index of the new image effect in a collection.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```


Adds the new Alpha Ceiling effect to the end of a collection.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index of the new image effect in a collection.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```


Adds the new Alpha Floor effect to the end of a collection.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index of the new image effect in a collection.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```


Adds the new Alpha Inverse effect to the end of a collection.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index of the new image effect in a collection.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```


Adds the new Alpha Modulate effect to the end of a collection.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index of the new image effect in a collection.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Adds the new Alpha Modulate Fixed effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | The percentage amount to scale the alpha. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index of the new image effect in a collection.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Adds the new Alpha Replace effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | The new opacity value. |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index of the new image effect in a collection.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```


Adds the new Bi-Level (black/white) effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | the luminance threshold for the Bi-Level effect. Values greater than or equal to the threshold are set to white. Values lesser than the threshold are set to black. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index of the new image effect in a collection.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```


Adds the new Blur effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | The radius of blur. |
| grow | boolean | Specifies whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Index of the new image effect in a collection.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```


Adds the new Color Change effect to the end of a collection.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index of the new image effect in a collection.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```


Adds the new Color Replacement effect to the end of a collection.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index of the new image effect in a collection.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```


Adds the new Duotone effect to the end of a collection.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Index of the new image effect in a collection.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```


Adds the new Fill Overlay effect to the end of a collection.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index of the new image effect in a collection.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```


Adds the new Gray Scale effect to the end of a collection.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index of the new image effect in a collection.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Adds the new Hue/Saturation/Luminance effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | The number of degrees by which the hue is adjusted. |
| saturation | float | The percentage by which the saturation is adjusted. |
| luminance | float | The percentage by which the luminance is adjusted. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - Index of the new image effect in a collection.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```


Adds the new Luminance effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | The percent to change the brightness. |
| contrast | float | The percent to change the contrast. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Index of the new image effect in a collection.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```


Adds the new Tint effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | The hue towards which to tint. |
| amount | float | Specifies by how much the color value is shifted. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Index of the new image effect in a collection.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Adds the new BrightnessContrast effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | The percent to change the brightness. |
| contrast | float | The percent to change the contrast. |

**Returns:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index of the new image effect in a collection.
