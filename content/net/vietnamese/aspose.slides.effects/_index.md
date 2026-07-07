---
title: Aspose.Slides.Effects
second_title: Tham khảo API .NET của Aspose.Sildes
description: Chứa các lớp để làm việc với các hiệu ứng khác nhau trong bản trình bày Microsoft PowerPoint.
type: docs
weight: 60
url: /vi/aspose.slides.effects/
---
Chứa các lớp để làm việc với các hiệu ứng khác nhau trong bản trình bày Microsoft PowerPoint.

## Các lớp

| Lớp | Mô tả |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Biểu diễn một Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [AlphaCeiling](./alphaceiling) | Biểu diễn một Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [AlphaFloor](./alphafloor) | Biểu diễn một Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [AlphaInverse](./alphainverse) | Biểu diễn một Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [AlphaModulate](./alphamodulate) | Biểu diễn một Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [AlphaModulateFixed](./alphamodulatefixed) | Biểu diễn một Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [AlphaReplace](./alphareplace) | Biểu diễn và Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| [BiLevel](./bilevel) | Biểu diễn một Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| [Blur](./blur) | Biểu diễn một Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [BrightnessContrast](./brightnesscontrast) | Biểu diễn một BrightnessContrast effect. Ajusts brightness and contrast |
| [ColorChange](./colorchange) | Biểu diễn một Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [ColorReplace](./colorreplace) | Biểu diễn một Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| [Duotone](./duotone) | Biểu diễn một Duotone effect. For each pixel, combines Color1 and Color2 through a linear interpolation to determine the new color for that pixel. |
| [EffectFactory](./effectfactory) | Cho phép tạo effects |
| [FillOverlay](./filloverlay) | Biểu diễn một Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [Glow](./glow) | Biểu diễn một Glow effect, in which a color blurred outline is added outside the edges of the object. |
| [GrayScale](./grayscale) | Biểu diễn một Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| [HSL](./hsl) | Biểu diễn một Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Immutable object that represents a readonly collection of effective image transform effects. |
| [ImageTransformOperation](./imagetransformoperation) | Biểu diễn abstract image transformation effect. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Biểu diễn một collection of effects apllied to an image. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Cho phép tạo image transform operations |
| [InnerShadow](./innershadow) | Biểu diễn một Inner Shadow effect. |
| [Luminance](./luminance) | Biểu diễn một Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [OuterShadow](./outershadow) | Biểu diễn một Outer Shadow effect. |
| [PresetShadow](./presetshadow) | Biểu diễn một Preset Shadow effect. |
| [Reflection](./reflection) | Biểu diễn một Reflection effect. |
| [SoftEdge](./softedge) | Biểu diễn một soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [Tint](./tint) | Biểu diễn một Tint effect. Shifts effect color values towards/away from hue by the specified amount. |

## Giao diện

| Giao diện | Mô tả |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Biểu diễn một Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Immutable object which represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaCeiling](./ialphaceiling) | Biểu diễn một Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Immutable object which represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque. |
| [IAlphaFloor](./ialphafloor) | Biểu diễn một Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Immutable object which represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent. |
| [IAlphaInverse](./ialphainverse) | Biểu diễn một Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Immutable object which represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaModulate](./ialphamodulate) | Biểu diễn một Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Immutable object which represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Biểu diễn một Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Immutable object which represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage. |
| [IAlphaReplace](./ialphareplace) | Biểu diễn base IImageTransformOperation interface. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Immutable object which represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha. |
| [IBiLevel](./ibilevel) | Biểu diễn base IImageTransformOperation interface. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Immutable object which represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect. |
| [IBlur](./iblur) | Biểu diễn một Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [IBlurEffectiveData](./iblureffectivedata) | Immutable object which represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected. |
| [IBrightnessContrast](./ibrightnesscontrast) | Biểu diễn một BrightnessContrast effect. Ajusts brightness and contrast |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Immutable object which represents a BrightnessContrast effect. Ajusts brightness and contrast |
| [IColorChange](./icolorchange) | Biểu diễn một Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Immutable object which represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor. |
| [IColorReplace](./icolorreplace) | Biểu diễn một Color Replacement effect. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Immutable object which represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected. |
| [IDuotone](./iduotone) | Biểu diễn một Duotone effect. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Immutable object which represents a Duotone effect. For each pixel, combines clr1 and clr2 through a linear interpolation to determine the new color for that pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Base class for immutable objects, which represent effect. |
| [IEffectFactory](./ieffectfactory) | Cho phép tạo instances of effects |
| [IFillOverlay](./ifilloverlay) | Biểu diễn một Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Immutable object which represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together. |
| [IGlow](./iglow) | Biểu diễn một Glow effect, in which a color blurred outline is added outside the edges of the object. |
| [IGlowEffectiveData](./igloweffectivedata) | Immutable object which represents a Glow effect, in which a color blurred outline is added outside the edges of the object. |
| [IGrayScale](./igrayscale) | Biểu diễn IImageTransformOperation interface. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Immutable object which representsepresents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected. |
| [IHSL](./ihsl) | Biểu diễn một Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [IHSLEffectiveData](./ihsleffectivedata) | Biểu diễn một Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Immutable object that represents a readonly collection of effective image transform effects. |
| [IImageTransformOperation](./iimagetransformoperation) | Biểu diễn abstract image transformation effect. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Biểu diễn một collection of effects apllied to an image. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Cho phép tạo instances of image effects |
| [IInnerShadow](./iinnershadow) | Biểu diễn một inner shadow effect. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Immutable object which represents a inner shadow effect. |
| [ILuminance](./iluminance) | Biểu diễn một Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Biểu diễn một Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart. |
| [IOuterShadow](./ioutershadow) | Biểu diễn một Outer Shadow effect. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Immutable object which represents an Outer Shadow effect. |
| [IPresetShadow](./ipresetshadow) | Biểu diễn một Preset Shadow effect. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Immutable object which represents a Preset Shadow effect. |
| [IReflection](./ireflection) | Biểu diễn một reflection effect. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Immutable object which represents a Reflection effect. |
| [ISoftEdge](./isoftedge) | Biểu diễn một Soft Edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Immutable object which represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected. |
| [ITint](./itint) | Biểu diễn một Tint effect. Shifts effect color values towards/away from hue by the specified amount. |
| [ITintEffectiveData](./itinteffectivedata) | Immutable object which represents a Tint effect. Shifts effect color values towards/away from hue by the specified amount. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->