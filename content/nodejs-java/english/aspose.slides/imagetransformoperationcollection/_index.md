---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/imagetransformoperationcollection/
---

## ImageTransformOperationCollection class

 Represents a collection of effects apllied to an image.
 
| [addAlphaBiLevelEffect] ([float]) Adds the new Alpha Bi-Level effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| threshold | [float] | The threshold value for the alpha bi-level effect. |

### Result
[AlphaBiLevel]


---


| [addAlphaCeilingEffect] () Adds the new Alpha Ceiling effect to the end of a collection. |

### Result
[AlphaCeiling]


---


| [addAlphaFloorEffect] () Adds the new Alpha Floor effect to the end of a collection. |

### Result
[AlphaFloor]


---


| [addAlphaInverseEffect] () Adds the new Alpha Inverse effect to the end of a collection. |

### Result
[AlphaInverse]


---


| [addAlphaModulateEffect] () Adds the new Alpha Modulate effect to the end of a collection. |

### Result
[AlphaModulate]


---


| [addAlphaModulateFixedEffect] ([float]) Adds the new Alpha Modulate Fixed effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| amount | [float] | The percentage amount to scale the alpha. |

### Result
[AlphaModulateFixed]


---


| [addAlphaReplaceEffect] ([float]) Adds the new Alpha Replace effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| alpha | [float] | The new opacity value. |

### Result
[AlphaReplace]


---


| [addBiLevelEffect] ([float]) Adds the new Bi-Level (black/white) effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| threshold | [float] | the luminance threshold for the Bi-Level effect. Values greater than or equal to the threshold are set to white. Values lesser than the threshold are set to black. |

### Result
[BiLevel]


---


| [addBlurEffect] ([double], [boolean]) Adds the new Blur effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| radius | [double] | The radius of blur. |
| grow | [boolean] | Specifies whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. |

### Result
[Blur]


---


| [addColorChangeEffect] () Adds the new Color Change effect to the end of a collection. |

### Result
[ColorChange]


---


| [addColorReplaceEffect] () Adds the new Color Replacement effect to the end of a collection. |

### Result
[ColorReplace]


---


| [addDuotoneEffect] () Adds the new Duotone effect to the end of a collection. |

### Result
[Duotone]


---


| [addFillOverlayEffect] () Adds the new Fill Overlay effect to the end of a collection. |

### Result
[FillOverlay]


---


| [addGrayScaleEffect] () Adds the new Gray Scale effect to the end of a collection. |

### Result
[GrayScale]


---


| [addHSLEffect] ([float], [float], [float]) Adds the new Hue/Saturation/Luminance effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hue | [float] | The number of degrees by which the hue is adjusted. |
| saturation | [float] | The percentage by which the saturation is adjusted. |
| luminance | [float] | The percentage by which the luminance is adjusted. |

### Result
[HSL]


---


| [addItem] ([AlphaFloor]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaFloor] | The image effect to add to the end of a collection. |


---


| [addItem] ([Luminance]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Luminance] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaModulate]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulate] | The image effect to add to the end of a collection. |


---


| [addItem] ([BiLevel]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [BiLevel] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaModulateFixed]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaModulateFixed] | The image effect to add to the end of a collection. |


---


| [addItem] ([Blur]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Blur] | The image effect to add to the end of a collection. |


---


| [addItem] ([Glow]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Glow] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaCeiling]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaCeiling] | The image effect to add to the end of a collection. |


---


| [addItem] ([ColorReplace]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorReplace] | The image effect to add to the end of a collection. |


---


| [addItem] ([GrayScale]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [GrayScale] | The image effect to add to the end of a collection. |


---


| [addItem] ([OuterShadow]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [OuterShadow] | The image effect to add to the end of a collection. |


---


| [addItem] ([Tint]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Tint] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaBiLevel]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaBiLevel] | The image effect to add to the end of a collection. |


---


| [addItem] ([Reflection]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Reflection] | The image effect to add to the end of a collection. |


---


| [addItem] ([FillOverlay]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [FillOverlay] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaReplace]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaReplace] | The image effect to add to the end of a collection. |


---


| [addItem] ([PresetShadow]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [PresetShadow] | The image effect to add to the end of a collection. |


---


| [addItem] ([HSL]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [HSL] | The image effect to add to the end of a collection. |


---


| [addItem] ([SoftEdge]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [SoftEdge] | The image effect to add to the end of a collection. |


---


| [addItem] ([InnerShadow]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [InnerShadow] | The image effect to add to the end of a collection. |


---


| [addItem] ([Duotone]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [Duotone] | The image effect to add to the end of a collection. |


---


| [addItem] ([AlphaInverse]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [AlphaInverse] | The image effect to add to the end of a collection. |


---


| [addItem] ([ColorChange]) Adds the new image effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorChange] | The image effect to add to the end of a collection. |


---


| [addLuminanceEffect] ([float], [float]) Adds the new Luminance effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| brightness | [float] | The percent to change the brightness. |
| contrast | [float] | The percent to change the contrast. |

### Result
[Luminance]


---


| [addTintEffect] ([float], [float]) Adds the new Tint effect to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| hue | [float] | The hue towards which to tint. |
| amount | [float] | Specifies by how much the color value is shifted. |

### Result
[Tint]


---


| [clear] () Removes all image effects from a collection. |


---


| [containsItem] ([AlphaFloor]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Luminance]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaModulate]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([BiLevel]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaModulateFixed]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Blur]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Glow]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaCeiling]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([ColorReplace]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([GrayScale]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([OuterShadow]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Tint]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaBiLevel]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Reflection]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([FillOverlay]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaReplace]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([PresetShadow]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([HSL]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([SoftEdge]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([InnerShadow]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([Duotone]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([AlphaInverse]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [containsItem] ([ColorChange]) Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [copyToTArray] ([com.aspose.slides.IImageTransformOperation[]], [int]) Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | [com.aspose.slides.IImageTransformOperation[]] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | [int] | The zero-based index in array at which copying begins. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


| [getVersion] ()  |

### Result
long


---


| [get_Item] ([int]) Returns an ImageTransformOperation from the collection by it's index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of element. |

### Result
[ImageTransformOperation], [AlphaFloor], [Luminance], [AlphaModulate], [BiLevel], [AlphaModulateFixed], [Blur], [Glow], [AlphaCeiling], [ColorReplace], [GrayScale], [OuterShadow], [Tint], [AlphaBiLevel], [Reflection], [FillOverlay], [AlphaReplace], [PresetShadow], [HSL], [SoftEdge], [InnerShadow], [Duotone], [AlphaInverse], [ColorChange]


---


| [isReadOnly] () Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [removeAt] ([int]) Removes an image effect from a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of an image effect that should be deleted. |


---


| [removeItem] ([AlphaFloor]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Luminance]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaModulate]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([BiLevel]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaModulateFixed]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Blur]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Glow]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaCeiling]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([ColorReplace]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([GrayScale]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([OuterShadow]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Tint]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaBiLevel]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Reflection]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([FillOverlay]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaReplace]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([PresetShadow]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([HSL]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([SoftEdge]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([InnerShadow]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([Duotone]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([AlphaInverse]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeItem] ([ColorChange]) Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [size] () Returns the number of image effects in a collection. Read-only int. |

### Result
int


---


