---
title: "Aspose::Slides::Effects"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 66
url: /cpp/aspose.slides.effects/
---



## Classes

| Class | Description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel/) | Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [AlphaCeiling](./alphaceiling/) | Represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [AlphaFloor](./alphafloor/) | Represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [AlphaInverse](./alphainverse/) | Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [AlphaModulate](./alphamodulate/) | Represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [AlphaModulateFixed](./alphamodulatefixed/) | Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [AlphaReplace](./alphareplace/) | Represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| [BiLevel](./bilevel/) | Represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| [Blur](./blur/) | Represents a [Blur](./blur/) effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [ColorChange](./colorchange/) | Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [ColorReplace](./colorreplace/) | Represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| [Duotone](./duotone/) | Represents a [Duotone](./duotone/) effect. For each pixel, combines Color1 and Color2 through a linear interpolation to determine the new color for that pixel. |
| [EffectFactory](./effectfactory/) | Allows to create effects |
| [FillOverlay](./filloverlay/) | Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [Glow](./glow/) | Represents a [Glow](./glow/) effect, in which a color blurred outline is added outside the edges of the object. |
| [GrayScale](./grayscale/) | Represents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| [HSL](./hsl/) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [IAlphaBiLevel](./ialphabilevel/) | Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata/) | Immutable object which represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaCeiling](./ialphaceiling/) | Represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata/) | Immutable object which represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [IAlphaFloor](./ialphafloor/) | Represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata/) | Immutable object which represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [IAlphaInverse](./ialphainverse/) | Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata/) | Immutable object which represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaModulate](./ialphamodulate/) | Represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata/) | Immutable object which represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [IAlphaModulateFixed](./ialphamodulatefixed/) | Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata/) | Immutable object which represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [IAlphaReplace](./ialphareplace/) | Represents base [IImageTransformOperation](./iimagetransformoperation/) interface. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata/) | Immutable object which represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| [IApplicableEffect](./iapplicableeffect/) |  |
| [IBiLevel](./ibilevel/) | Represents base [IImageTransformOperation](./iimagetransformoperation/) interface. |
| [IBiLevelEffectiveData](./ibileveleffectivedata/) | Immutable object which represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| [IBlur](./iblur/) | Represents a [Blur](./blur/) effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [IBlurEffectiveData](./iblureffectivedata/) | Immutable object which represents a [Blur](./blur/) effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [IColorChange](./icolorchange/) | Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata/) | Immutable object which represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [IColorReplace](./icolorreplace/) | Represents a Color Replacement effect. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata/) | Immutable object which represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| [IDuotone](./iduotone/) | Represents a [Duotone](./duotone/) effect. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata/) | Immutable object which represents a [Duotone](./duotone/) effect. For each pixel, combines clr1 and clr2 through a linear interpolation to determine the new color for that pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata/) | Base class for immutable objects, which represent effect. |
| [IEffectFactory](./ieffectfactory/) | Allows to create effects' instances |
| [IFillOverlay](./ifilloverlay/) | Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata/) | Immutable object which represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [IGlow](./iglow/) | Represents a [Glow](./glow/) effect, in which a color blurred outline is added outside the edges of the object. |
| [IGlowEffectiveData](./igloweffectivedata/) | Immutable object which represents a [Glow](./glow/) effect, in which a color blurred outline is added outside the edges of the object. |
| [IGrayScale](./igrayscale/) | Represents [IImageTransformOperation](./iimagetransformoperation/) interface. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata/) | Immutable object which representsepresents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| [IHSL](./ihsl/) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [IHSLEffectiveData](./ihsleffectivedata/) | Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata/) | Immutable object that represents a readonly collection of effective image transform effects. |
| [IImageTransformOperation](./iimagetransformoperation/) | Represents abstract image transformation effect. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection/) | Represents a collection of effects apllied to an image. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory/) | Allows to create image effects' instances |
| [IInnerShadow](./iinnershadow/) | Represents a inner shadow effect. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata/) | Immutable object which represents a inner shadow effect. |
| [ILuminance](./iluminance/) | Represents a [Luminance](./luminance/) effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata/) | Represents a [Luminance](./luminance/) effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata/) | Immutable object that represents a readonly collection of effective image transform effects. |
| [ImageTransformOperation](./imagetransformoperation/) | Represents abstract image transformation effect. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection/) | Represents a collection of effects apllied to an image. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory/) | Allows to create image transform operations |
| [InnerShadow](./innershadow/) | Represents a Inner Shadow effect. |
| [IOuterShadow](./ioutershadow/) | Represents an Outer Shadow effect. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata/) | Immutable object which represents an Outer Shadow effect. |
| [IPresetShadow](./ipresetshadow/) | Represents a Preset Shadow effect. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata/) | Immutable object which represents a Preset Shadow effect. |
| [IReflection](./ireflection/) | Represents a reflection effect. |
| [IReflectionEffectiveData](./ireflectioneffectivedata/) | Immutable object which represents a [Reflection](./reflection/) effect. |
| [ISoftEdge](./isoftedge/) | Represents a Soft Edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata/) | Immutable object which represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [ITint](./itint/) | Represents a [Tint](./tint/) effect. Shifts effect color values towards/away from hue by the specified amount. |
| [ITintEffectiveData](./itinteffectivedata/) | Immutable object which represents a [Tint](./tint/) effect. Shifts effect color values towards/away from hue by the specified amount. |
| [IVisualEffect](./ivisualeffect/) |  |
| [Luminance](./luminance/) | Represents a [Luminance](./luminance/) effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [OuterShadow](./outershadow/) | Represents an Outer Shadow effect. |
| [PresetShadow](./presetshadow/) | Represents a Preset Shadow effect. |
| [Reflection](./reflection/) | Represents a [Reflection](./reflection/) effect. |
| [SoftEdge](./softedge/) | Represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [Tint](./tint/) | Represents a [Tint](./tint/) effect. Shifts effect color values towards/away from hue by the specified amount. |
