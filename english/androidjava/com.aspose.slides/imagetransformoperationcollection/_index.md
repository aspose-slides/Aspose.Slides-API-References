---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of effects apllied to an image.
type: docs
weight: 251
url: /androidjava/com.aspose.slides/imagetransformoperationcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Represents a collection of effects apllied to an image.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns an [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) from the collection by it's index. |
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
| [size()](#size--) | Returns the number of image effects in a collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Adds the new image effect to the end of a collection. |
| [clear()](#clear--) | Removes all image effects from a collection. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```


Returns an [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) from the collection by it's index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - The [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) object.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes an image effect from a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of an image effect that should be deleted. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
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
public final IAlphaCeiling addAlphaCeilingEffect()
```


Adds the new Alpha Ceiling effect to the end of a collection.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index of the new image effect in a collection.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Adds the new Alpha Floor effect to the end of a collection.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index of the new image effect in a collection.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Adds the new Alpha Inverse effect to the end of a collection.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index of the new image effect in a collection.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Adds the new Alpha Modulate effect to the end of a collection.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index of the new image effect in a collection.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
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
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
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
public final IBiLevel addBiLevelEffect(float threshold)
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
public final IBlur addBlurEffect(double radius, boolean grow)
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
public final IColorChange addColorChangeEffect()
```


Adds the new Color Change effect to the end of a collection.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index of the new image effect in a collection.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Adds the new Color Replacement effect to the end of a collection.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index of the new image effect in a collection.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Adds the new Duotone effect to the end of a collection.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Index of the new image effect in a collection.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Adds the new Fill Overlay effect to the end of a collection.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index of the new image effect in a collection.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Adds the new Gray Scale effect to the end of a collection.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index of the new image effect in a collection.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
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
public final ILuminance addLuminanceEffect(float brightness, float contrast)
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
public final ITint addTintEffect(float hue, float amount)
```


Adds the new Tint effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | The hue towards which to tint. |
| amount | float | Specifies by how much the color value is shifted. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Index of the new image effect in a collection.
### size() {#size--}
```
public final int size()
```


Returns the number of image effects in a collection. Read-only  int .

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**Returns:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Adds the new image effect to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | The image effect to add to the end of a collection. |

### clear() {#clear--}
```
public final void clear()
```


Removes all image effects from a collection.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | The object to remove from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if  item  was successfully removed from the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. This method also returns false if item is not found in the original [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - An java.util.Iterator for the entire collection.
