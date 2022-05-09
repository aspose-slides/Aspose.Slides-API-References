---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes for .NET API Reference
description: Contains classes for work with various effects in Microsoft PowerPoint presentations.
type: docs
weight: 50
url: /net/aspose.slides.effects/
---
Contains classes for work with various effects in Microsoft PowerPoint presentations.

## Classes

| Class | Description |
| --- | --- |
| class [AlphaBiLevel](./alphabilevel) | Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| class [AlphaCeiling](./alphaceiling) | Represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| class [AlphaFloor](./alphafloor) | Represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| class [AlphaInverse](./alphainverse) | Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| class [AlphaModulate](./alphamodulate) | Represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| class [AlphaModulateFixed](./alphamodulatefixed) | Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| class [AlphaReplace](./alphareplace) | Represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| class [BiLevel](./bilevel) | Represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| class [Blur](./blur) | Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| class [ColorChange](./colorchange) | Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| class [ColorReplace](./colorreplace) | Represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| class [Duotone](./duotone) | Represents a Duotone effect. For each pixel, combines Color1 and Color2 through a linear interpolation to determine the new color for that pixel. |
| class [EffectFactory](./effectfactory) | Allows to create effects |
| class [FillOverlay](./filloverlay) | Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| class [Glow](./glow) | Represents a Glow effect, in which a color blurred outline is added outside the edges of the object. |
| class [GrayScale](./grayscale) | Represents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| class [HSL](./hsl) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| class [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Immutable object that represents a readonly collection of effective image transform effects. |
| abstract class [ImageTransformOperation](./imagetransformoperation) | Represents abstract image transformation effect. |
| class [ImageTransformOperationCollection](./imagetransformoperationcollection) | Represents a collection of effects apllied to an image. |
| class [ImageTransformOperationFactory](./imagetransformoperationfactory) | Allows to create image transform operations |
| class [InnerShadow](./innershadow) | Represents a Inner Shadow effect. |
| class [Luminance](./luminance) | Represents a Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| class [OuterShadow](./outershadow) | Represents an Outer Shadow effect. |
| class [PresetShadow](./presetshadow) | Represents a Preset Shadow effect. |
| class [Reflection](./reflection) | Represents a Reflection effect. |
| class [SoftEdge](./softedge) | Represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| class [Tint](./tint) | Represents a Tint effect. Shifts effect color values towards/away from hue by the specified amount. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IAlphaBiLevel](./ialphabilevel) | Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| interface [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Immutable object which represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| interface [IAlphaCeiling](./ialphaceiling) | Represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| interface [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Immutable object which represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| interface [IAlphaFloor](./ialphafloor) | Represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| interface [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Immutable object which represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| interface [IAlphaInverse](./ialphainverse) | Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| interface [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Immutable object which represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| interface [IAlphaModulate](./ialphamodulate) | Represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| interface [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Immutable object which represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| interface [IAlphaModulateFixed](./ialphamodulatefixed) | Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| interface [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Immutable object which represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| interface [IAlphaReplace](./ialphareplace) | Represents base IImageTransformOperation interface. |
| interface [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Immutable object which represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| interface [IBiLevel](./ibilevel) | Represents base IImageTransformOperation interface. |
| interface [IBiLevelEffectiveData](./ibileveleffectivedata) | Immutable object which represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| interface [IBlur](./iblur) | Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| interface [IBlurEffectiveData](./iblureffectivedata) | Immutable object which represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| interface [IColorChange](./icolorchange) | Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| interface [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Immutable object which represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| interface [IColorReplace](./icolorreplace) | Represents a Color Replacement effect. |
| interface [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Immutable object which represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| interface [IDuotone](./iduotone) | Represents a Duotone effect. |
| interface [IDuotoneEffectiveData](./iduotoneeffectivedata) | Immutable object which represents a Duotone effect. For each pixel, combines clr1 and clr2 through a linear interpolation to determine the new color for that pixel. |
| interface [IEffectEffectiveData](./ieffecteffectivedata) | Base class for immutable objects, which represent effect. |
| interface [IEffectFactory](./ieffectfactory) | Allows to create effects' instances |
| interface [IFillOverlay](./ifilloverlay) | Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| interface [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Immutable object which represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| interface [IGlow](./iglow) | Represents a Glow effect, in which a color blurred outline is added outside the edges of the object. |
| interface [IGlowEffectiveData](./igloweffectivedata) | Immutable object which represents a Glow effect, in which a color blurred outline is added outside the edges of the object. |
| interface [IGrayScale](./igrayscale) | Represents IImageTransformOperation interface. |
| interface [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Immutable object which representsepresents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| interface [IHSL](./ihsl) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| interface [IHSLEffectiveData](./ihsleffectivedata) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| interface [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Immutable object that represents a readonly collection of effective image transform effects. |
| interface [IImageTransformOperation](./iimagetransformoperation) | Represents abstract image transformation effect. |
| interface [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Represents a collection of effects apllied to an image. |
| interface [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Allows to create image effects' instances |
| interface [IInnerShadow](./iinnershadow) | Represents a inner shadow effect. |
| interface [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Immutable object which represents a inner shadow effect. |
| interface [ILuminance](./iluminance) | Represents a Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| interface [ILuminanceEffectiveData](./iluminanceeffectivedata) | Represents a Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| interface [IOuterShadow](./ioutershadow) | Represents an Outer Shadow effect. |
| interface [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Immutable object which represents an Outer Shadow effect. |
| interface [IPresetShadow](./ipresetshadow) | Represents a Preset Shadow effect. |
| interface [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Immutable object which represents a Preset Shadow effect. |
| interface [IReflection](./ireflection) | Represents a reflection effect. |
| interface [IReflectionEffectiveData](./ireflectioneffectivedata) | Immutable object which represents a Reflection effect. |
| interface [ISoftEdge](./isoftedge) | Represents a Soft Edge effect. The edges of the shape are blurred, while the fill is not affected. |
| interface [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Immutable object which represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| interface [ITint](./itint) | Represents a Tint effect. Shifts effect color values towards/away from hue by the specified amount. |
| interface [ITintEffectiveData](./itinteffectivedata) | Immutable object which represents a Tint effect. Shifts effect color values towards/away from hue by the specified amount. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
