---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/imagetransformoperationcollection/
---

## ImageTransformOperationCollection class

 Represents a collection of effects apllied to an image.
 

## Functions

| Name | Description |
| --- | --- |
| [addAlphaBiLevelEffect](float) | Adds the new Alpha Bi-Level effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | The threshold value for the alpha bi-level effect. |

### Result
[AlphaBiLevel](../../alphabilevel)


---


| [addAlphaCeilingEffect]() | Adds the new Alpha Ceiling effect to the end of a collection. |

### Result
[AlphaCeiling](../../alphaceiling)


---


| [addAlphaFloorEffect]() | Adds the new Alpha Floor effect to the end of a collection. |

### Result
[AlphaFloor](../../alphafloor)


---


| [addAlphaInverseEffect]() | Adds the new Alpha Inverse effect to the end of a collection. |

### Result
[AlphaInverse](../../alphainverse)


---


| [addAlphaModulateEffect]() | Adds the new Alpha Modulate effect to the end of a collection. |

### Result
[AlphaModulate](../../alphamodulate)


---


| [addAlphaModulateFixedEffect](float) | Adds the new Alpha Modulate Fixed effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| amount | float | The percentage amount to scale the alpha. |

### Result
[AlphaModulateFixed](../../alphamodulatefixed)


---


| [addAlphaReplaceEffect](float) | Adds the new Alpha Replace effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| alpha | float | The new opacity value. |

### Result
[AlphaReplace](../../alphareplace)


---


| [addBiLevelEffect](float) | Adds the new Bi-Level (black/white) effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| threshold | float | the luminance threshold for the Bi-Level effect. Values greater than or equal to the threshold are set to white. Values lesser than the threshold are set to black. |

### Result
[BiLevel](../../bilevel)


---


| [addBlurEffect](double, boolean) | Adds the new Blur effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| radius | double | The radius of blur. |
| grow | boolean | Specifies whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. |

### Result
[Blur](../../blur)


---


| [addColorChangeEffect]() | Adds the new Color Change effect to the end of a collection. |

### Result
[ColorChange](../../colorchange)


---


| [addColorReplaceEffect]() | Adds the new Color Replacement effect to the end of a collection. |

### Result
[ColorReplace](../../colorreplace)


---


| [addDuotoneEffect]() | Adds the new Duotone effect to the end of a collection. |

### Result
[Duotone](../../duotone)


---


| [addFillOverlayEffect]() | Adds the new Fill Overlay effect to the end of a collection. |

### Result
[FillOverlay](../../filloverlay)


---


| [addGrayScaleEffect]() | Adds the new Gray Scale effect to the end of a collection. |

### Result
[GrayScale](../../grayscale)


---


| [addHSLEffect](float, float, float) | Adds the new Hue/Saturation/Luminance effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hue | float | The number of degrees by which the hue is adjusted. |
| saturation | float | The percentage by which the saturation is adjusted. |
| luminance | float | The percentage by which the luminance is adjusted. |

### Result
[HSL](../../hsl)


---


| [addItem]([AlphaFloor](../alphafloor)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaFloor](../../alphafloor) | The image effect to add to the end of a collection. |


---


| [addItem]([Luminance](../luminance)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Luminance](../../luminance) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaModulate](../alphamodulate)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulate](../../alphamodulate) | The image effect to add to the end of a collection. |


---


| [addItem]([BiLevel](../bilevel)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [BiLevel](../../bilevel) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaModulateFixed](../alphamodulatefixed)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulateFixed](../../alphamodulatefixed) | The image effect to add to the end of a collection. |


---


| [addItem]([Blur](../blur)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Blur](../../blur) | The image effect to add to the end of a collection. |


---


| [addItem]([Glow](../glow)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Glow](../../glow) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaCeiling](../alphaceiling)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaCeiling](../../alphaceiling) | The image effect to add to the end of a collection. |


---


| [addItem]([ColorReplace](../colorreplace)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorReplace](../../colorreplace) | The image effect to add to the end of a collection. |


---


| [addItem]([GrayScale](../grayscale)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [GrayScale](../../grayscale) | The image effect to add to the end of a collection. |


---


| [addItem]([OuterShadow](../outershadow)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [OuterShadow](../../outershadow) | The image effect to add to the end of a collection. |


---


| [addItem]([Tint](../tint)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Tint](../../tint) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaBiLevel](../alphabilevel)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaBiLevel](../../alphabilevel) | The image effect to add to the end of a collection. |


---


| [addItem]([Reflection](../reflection)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Reflection](../../reflection) | The image effect to add to the end of a collection. |


---


| [addItem]([FillOverlay](../filloverlay)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [FillOverlay](../../filloverlay) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaReplace](../alphareplace)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaReplace](../../alphareplace) | The image effect to add to the end of a collection. |


---


| [addItem]([PresetShadow](../presetshadow)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [PresetShadow](../../presetshadow) | The image effect to add to the end of a collection. |


---


| [addItem]([HSL](../hsl)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [HSL](../../hsl) | The image effect to add to the end of a collection. |


---


| [addItem]([SoftEdge](../softedge)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [SoftEdge](../../softedge) | The image effect to add to the end of a collection. |


---


| [addItem]([InnerShadow](../innershadow)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [InnerShadow](../../innershadow) | The image effect to add to the end of a collection. |


---


| [addItem]([Duotone](../duotone)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Duotone](../../duotone) | The image effect to add to the end of a collection. |


---


| [addItem]([AlphaInverse](../alphainverse)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaInverse](../../alphainverse) | The image effect to add to the end of a collection. |


---


| [addItem]([ColorChange](../colorchange)) | Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorChange](../../colorchange) | The image effect to add to the end of a collection. |


---


| [addLuminanceEffect](float, float) | Adds the new Luminance effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| brightness | float | The percent to change the brightness. |
| contrast | float | The percent to change the contrast. |

### Result
[Luminance](../../luminance)


---


| [addTintEffect](float, float) | Adds the new Tint effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hue | float | The hue towards which to tint. |
| amount | float | Specifies by how much the color value is shifted. |

### Result
[Tint](../../tint)


---


| [clear]() | Removes all image effects from a collection. |


---


| [containsItem]([AlphaFloor](../alphafloor)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../../alphafloor) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Luminance](../luminance)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance](../../luminance) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaModulate](../alphamodulate)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../../alphamodulate) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([BiLevel](../bilevel)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../../bilevel) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaModulateFixed](../alphamodulatefixed)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../../alphamodulatefixed) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Blur](../blur)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur](../../blur) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Glow](../glow)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow](../../glow) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaCeiling](../alphaceiling)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../../alphaceiling) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([ColorReplace](../colorreplace)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../../colorreplace) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([GrayScale](../grayscale)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../../grayscale) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([OuterShadow](../outershadow)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../../outershadow) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Tint](../tint)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint](../../tint) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaBiLevel](../alphabilevel)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../../alphabilevel) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Reflection](../reflection)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection](../../reflection) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([FillOverlay](../filloverlay)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../../filloverlay) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaReplace](../alphareplace)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../../alphareplace) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([PresetShadow](../presetshadow)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../../presetshadow) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([HSL](../hsl)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL](../../hsl) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([SoftEdge](../softedge)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../../softedge) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([InnerShadow](../innershadow)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../../innershadow) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([Duotone](../duotone)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone](../../duotone) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([AlphaInverse](../alphainverse)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../../alphainverse) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem]([ColorChange](../colorchange)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../../colorchange) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [copyToTArray](com.aspose.slides.IImageTransformOperation[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IImageTransformOperation[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


| [getVersion]() |  |

### Result
long


---


| [get_Item](int) | Returns an ImageTransformOperation from the collection by it's index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

### Result
[ImageTransformOperation](../../imagetransformoperation), [AlphaFloor](../../alphafloor), [Luminance](../../luminance), [AlphaModulate](../../alphamodulate), [BiLevel](../../bilevel), [AlphaModulateFixed](../../alphamodulatefixed), [Blur](../../blur), [Glow](../../glow), [AlphaCeiling](../../alphaceiling), [ColorReplace](../../colorreplace), [GrayScale](../../grayscale), [OuterShadow](../../outershadow), [Tint](../../tint), [AlphaBiLevel](../../alphabilevel), [Reflection](../../reflection), [FillOverlay](../../filloverlay), [AlphaReplace](../../alphareplace), [PresetShadow](../../presetshadow), [HSL](../../hsl), [SoftEdge](../../softedge), [InnerShadow](../../innershadow), [Duotone](../../duotone), [AlphaInverse](../../alphainverse), [ColorChange](../../colorchange)


---


| [isReadOnly]() | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

### Result
boolean


---


| [iterator]() | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava]() | Returns a java iterator for the entire collection. |

### Result



---


| [removeAt](int) | Removes an image effect from a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of an image effect that should be deleted. |


---


| [removeItem]([AlphaFloor](../alphafloor)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../../alphafloor) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Luminance](../luminance)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance](../../luminance) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaModulate](../alphamodulate)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../../alphamodulate) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([BiLevel](../bilevel)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../../bilevel) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaModulateFixed](../alphamodulatefixed)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../../alphamodulatefixed) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Blur](../blur)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur](../../blur) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Glow](../glow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow](../../glow) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaCeiling](../alphaceiling)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../../alphaceiling) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([ColorReplace](../colorreplace)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../../colorreplace) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([GrayScale](../grayscale)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../../grayscale) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([OuterShadow](../outershadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../../outershadow) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Tint](../tint)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint](../../tint) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaBiLevel](../alphabilevel)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../../alphabilevel) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Reflection](../reflection)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection](../../reflection) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([FillOverlay](../filloverlay)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../../filloverlay) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaReplace](../alphareplace)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../../alphareplace) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([PresetShadow](../presetshadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../../presetshadow) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([HSL](../hsl)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL](../../hsl) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([SoftEdge](../softedge)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../../softedge) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([InnerShadow](../innershadow)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../../innershadow) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([Duotone](../duotone)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone](../../duotone) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([AlphaInverse](../alphainverse)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../../alphainverse) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem]([ColorChange](../colorchange)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../../colorchange) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [size]() | Returns the number of image effects in a collection. Read-only int. |

### Result
int


---


