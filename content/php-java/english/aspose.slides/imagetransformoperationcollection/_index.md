---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/imagetransformoperationcollection/
---

## ImageTransformOperationCollection class

 Represents a collection of effects apllied to an image.
 
### addAlphaBiLevelEffect {#addAlphaBiLevelEffect}

| Name | Description |
| --- | --- |
| addAlphaBiLevelEffect (float) | Adds the new Alpha Bi-Level effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | The threshold value for the alpha bi-level effect. |

 **Returns:**
[AlphaBiLevel](../alphabilevel)


---


### addAlphaCeilingEffect {#addAlphaCeilingEffect}

| Name | Description |
| --- | --- |
| addAlphaCeilingEffect () | Adds the new Alpha Ceiling effect to the end of a collection. |

 **Returns:**
[AlphaCeiling](../alphaceiling)


---


### addAlphaFloorEffect {#addAlphaFloorEffect}

| Name | Description |
| --- | --- |
| addAlphaFloorEffect () | Adds the new Alpha Floor effect to the end of a collection. |

 **Returns:**
[AlphaFloor](../alphafloor)


---


### addAlphaInverseEffect {#addAlphaInverseEffect}

| Name | Description |
| --- | --- |
| addAlphaInverseEffect () | Adds the new Alpha Inverse effect to the end of a collection. |

 **Returns:**
[AlphaInverse](../alphainverse)


---


### addAlphaModulateEffect {#addAlphaModulateEffect}

| Name | Description |
| --- | --- |
| addAlphaModulateEffect () | Adds the new Alpha Modulate effect to the end of a collection. |

 **Returns:**
[AlphaModulate](../alphamodulate)


---


### addAlphaModulateFixedEffect {#addAlphaModulateFixedEffect}

| Name | Description |
| --- | --- |
| addAlphaModulateFixedEffect (float) | Adds the new Alpha Modulate Fixed effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| amount | float | The percentage amount to scale the alpha. |

 **Returns:**
[AlphaModulateFixed](../alphamodulatefixed)


---


### addAlphaReplaceEffect {#addAlphaReplaceEffect}

| Name | Description |
| --- | --- |
| addAlphaReplaceEffect (float) | Adds the new Alpha Replace effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| alpha | float | The new opacity value. |

 **Returns:**
[AlphaReplace](../alphareplace)


---


### addBiLevelEffect {#addBiLevelEffect}

| Name | Description |
| --- | --- |
| addBiLevelEffect (float) | Adds the new Bi-Level (black/white) effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | the luminance threshold for the Bi-Level effect. Values greater than or equal to the threshold are set to white. Values lesser than the threshold are set to black. |

 **Returns:**
[BiLevel](../bilevel)


---


### addBlurEffect {#addBlurEffect}

| Name | Description |
| --- | --- |
| addBlurEffect (double, boolean) | Adds the new Blur effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| radius | double | The radius of blur. |
| grow | boolean | Specifies whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. |

 **Returns:**
[Blur](../blur)


---


### addColorChangeEffect {#addColorChangeEffect}

| Name | Description |
| --- | --- |
| addColorChangeEffect () | Adds the new Color Change effect to the end of a collection. |

 **Returns:**
[ColorChange](../colorchange)


---


### addColorReplaceEffect {#addColorReplaceEffect}

| Name | Description |
| --- | --- |
| addColorReplaceEffect () | Adds the new Color Replacement effect to the end of a collection. |

 **Returns:**
[ColorReplace](../colorreplace)


---


### addDuotoneEffect {#addDuotoneEffect}

| Name | Description |
| --- | --- |
| addDuotoneEffect () | Adds the new Duotone effect to the end of a collection. |

 **Returns:**
[Duotone](../duotone)


---


### addFillOverlayEffect {#addFillOverlayEffect}

| Name | Description |
| --- | --- |
| addFillOverlayEffect () | Adds the new Fill Overlay effect to the end of a collection. |

 **Returns:**
[FillOverlay](../filloverlay)


---


### addGrayScaleEffect {#addGrayScaleEffect}

| Name | Description |
| --- | --- |
| addGrayScaleEffect () | Adds the new Gray Scale effect to the end of a collection. |

 **Returns:**
[GrayScale](../grayscale)


---


### addHSLEffect {#addHSLEffect}

| Name | Description |
| --- | --- |
| addHSLEffect (float, float, float) | Adds the new Hue/Saturation/Luminance effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hue | float | The number of degrees by which the hue is adjusted. |
| saturation | float | The percentage by which the saturation is adjusted. |
| luminance | float | The percentage by which the luminance is adjusted. |

 **Returns:**
[HSL](../hsl)


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ImageTransformOperation](../imagetransformoperation)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [ImageTransformOperation](../imagetransformoperation) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([SoftEdge](../softedge)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [SoftEdge](../softedge) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([HSL](../hsl)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [HSL](../hsl) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaBiLevel](../alphabilevel)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaBiLevel](../alphabilevel) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([InnerShadow](../innershadow)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [InnerShadow](../innershadow) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ColorChange](../colorchange)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorChange](../colorchange) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaModulate](../alphamodulate)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulate](../alphamodulate) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Reflection](../reflection)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Reflection](../reflection) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Glow](../glow)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Glow](../glow) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaFloor](../alphafloor)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaFloor](../alphafloor) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaModulateFixed](../alphamodulatefixed)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulateFixed](../alphamodulatefixed) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([GrayScale](../grayscale)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [GrayScale](../grayscale) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Duotone](../duotone)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Duotone](../duotone) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Luminance](../luminance)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Luminance](../luminance) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaInverse](../alphainverse)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaInverse](../alphainverse) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaCeiling](../alphaceiling)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaCeiling](../alphaceiling) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([OuterShadow](../outershadow)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [OuterShadow](../outershadow) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Blur](../blur)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Blur](../blur) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([PresetShadow](../presetshadow)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [PresetShadow](../presetshadow) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([AlphaReplace](../alphareplace)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaReplace](../alphareplace) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([BiLevel](../bilevel)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [BiLevel](../bilevel) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ColorReplace](../colorreplace)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorReplace](../colorreplace) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Tint](../tint)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Tint](../tint) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([FillOverlay](../filloverlay)) | Adds the new image effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| operation | [FillOverlay](../filloverlay) | The image effect to add to the end of a collection. |

 **Returns:**
void


---


### addLuminanceEffect {#addLuminanceEffect}

| Name | Description |
| --- | --- |
| addLuminanceEffect (float, float) | Adds the new Luminance effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| brightness | float | The percent to change the brightness. |
| contrast | float | The percent to change the contrast. |

 **Returns:**
[Luminance](../luminance)


---


### addTintEffect {#addTintEffect}

| Name | Description |
| --- | --- |
| addTintEffect (float, float) | Adds the new Tint effect to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| hue | float | The hue towards which to tint. |
| amount | float | Specifies by how much the color value is shifted. |

 **Returns:**
[Tint](../tint)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all image effects from a collection. |

 **Returns:**
void


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ImageTransformOperation](../imagetransformoperation)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([SoftEdge](../softedge)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([HSL](../hsl)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL](../hsl) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaBiLevel](../alphabilevel)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([InnerShadow](../innershadow)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ColorChange](../colorchange)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaModulate](../alphamodulate)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Reflection](../reflection)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection](../reflection) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Glow](../glow)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow](../glow) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaFloor](../alphafloor)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaModulateFixed](../alphamodulatefixed)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([GrayScale](../grayscale)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Duotone](../duotone)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone](../duotone) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Luminance](../luminance)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance](../luminance) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaInverse](../alphainverse)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaCeiling](../alphaceiling)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([OuterShadow](../outershadow)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Blur](../blur)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur](../blur) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([PresetShadow](../presetshadow)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaReplace](../alphareplace)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([BiLevel](../bilevel)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ColorReplace](../colorreplace)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Tint](../tint)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint](../tint) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([FillOverlay](../filloverlay)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | The object to locate in the IGenericCollection. |

 **Returns:**
boolean


---


### copyToTArray {#copyToTArray}

| Name | Description |
| --- | --- |
| copyToTArray (com.aspose.slides.IImageTransformOperation[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IImageTransformOperation[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns an ImageTransformOperation from the collection by it's index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

 **Returns:**
[ImageTransformOperation](../imagetransformoperation), [SoftEdge](../softedge), [HSL](../hsl), [AlphaBiLevel](../alphabilevel), [InnerShadow](../innershadow), [ColorChange](../colorchange), [AlphaModulate](../alphamodulate), [Reflection](../reflection), [Glow](../glow), [AlphaFloor](../alphafloor), [AlphaModulateFixed](../alphamodulatefixed), [GrayScale](../grayscale), [Duotone](../duotone), [Luminance](../luminance), [AlphaInverse](../alphainverse), [AlphaCeiling](../alphaceiling), [OuterShadow](../outershadow), [Blur](../blur), [PresetShadow](../presetshadow), [AlphaReplace](../alphareplace), [BiLevel](../bilevel), [ColorReplace](../colorreplace), [Tint](../tint), [FillOverlay](../filloverlay)


---


### isReadOnly {#isReadOnly}

| Name | Description |
| --- | --- |
| isReadOnly () | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes an image effect from a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of an image effect that should be deleted. |

 **Returns:**
void


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([ImageTransformOperation](../imagetransformoperation)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([SoftEdge](../softedge)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([HSL](../hsl)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL](../hsl) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaBiLevel](../alphabilevel)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([InnerShadow](../innershadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([ColorChange](../colorchange)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaModulate](../alphamodulate)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Reflection](../reflection)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection](../reflection) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Glow](../glow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow](../glow) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaFloor](../alphafloor)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaModulateFixed](../alphamodulatefixed)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([GrayScale](../grayscale)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Duotone](../duotone)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone](../duotone) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Luminance](../luminance)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance](../luminance) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaInverse](../alphainverse)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaCeiling](../alphaceiling)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([OuterShadow](../outershadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Blur](../blur)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur](../blur) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([PresetShadow](../presetshadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([AlphaReplace](../alphareplace)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([BiLevel](../bilevel)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([ColorReplace](../colorreplace)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([Tint](../tint)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint](../tint) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeItem {#removeItem}

| Name | Description |
| --- | --- |
| removeItem ([FillOverlay](../filloverlay)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | The object to remove from the IGenericCollection. |

 **Returns:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns the number of image effects in a collection. Read-only int. |

 **Returns:**
int


---


