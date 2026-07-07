---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes for .NET API 參考
description: 包含用於在 Microsoft PowerPoint 簡報中處理各種效果的類別。
type: docs
weight: 60
url: /zh-hant/aspose.slides.effects/
---
包含用於在 Microsoft PowerPoint 簡報中處理各種效果的類別。

## Classes

| 類別 | 說明 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | 表示 Alpha Bi-Level 效果。Alpha（Opacity）值低於閾值的會被變為 0（完全透明），而大於或等於閾值的 Alpha 值會被變為 100%（完全不透明）。 |
| [AlphaCeiling](./alphaceiling) | 表示 Alpha Ceiling 效果。Alpha（opacity）值大於零的會被變為 100%。換句話說，任何部分不透明的物件將變為完全不透明。 |
| [AlphaFloor](./alphafloor) | 表示 Alpha Floor 效果。Alpha（opacity）值低於 100% 的會被變為 0。換句話說，任何部分透明的物件將變為完全透明。 |
| [AlphaInverse](./alphainverse) | 表示 Alpha Inverse 效果。Alpha（opacity）值透過從 100% 減去而反轉。 |
| [AlphaModulate](./alphamodulate) | 表示 Alpha Modulate 效果。效果的 alpha（opacity）值會乘以固定的百分比。效果容器指定包含要調變之 alpha 值的效果。 |
| [AlphaModulateFixed](./alphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。效果的 alpha（opacity）值會乘以固定的百分比。 |
| [AlphaReplace](./alphareplace) | 表示 Alpha Replace 效果。效果的 alpha（opacity）值會被固定的 alpha 所取代。 |
| [BiLevel](./bilevel) | 表示 Bi-Level（黑/白）效果。亮度低於指定閾值的輸入顏色會被變為黑色。亮度大於或等於指定值的輸入顏色會被設定為白色。此效果不會影響 alpha 效果值。 |
| [Blur](./blur) | 表示套用於整個圖形（包括填充）的 Blur 效果。所有色彩通道，包括 alpha，皆會受到影響。 |
| [BrightnessContrast](./brightnesscontrast) | 表示 BrightnessContrast 效果。調整亮度與對比度 |
| [ColorChange](./colorchange) | 表示 Color Change 效果。將 FromColor 的實例取代為 ToColor 的實例。 |
| [ColorReplace](./colorreplace) | 表示 Color Replacement 效果。所有效果顏色會被變更為固定顏色。Alpha 值不受影響。 |
| [Duotone](./duotone) | 表示 Duotone 效果。對每個像素，透過線性插值將 Color1 與 Color2 結合，以決定該像素的新顏色。 |
| [EffectFactory](./effectfactory) | 允許建立效果 |
| [FillOverlay](./filloverlay) | 表示 Fill Overlay 效果。可使用填充覆蓋層為物件指定額外的填充，並將兩個填充混合在一起。 |
| [Glow](./glow) | 表示 Glow 效果，會在物件邊緣外加入顏色模糊的輪廓。 |
| [GrayScale](./grayscale) | 表示 Gray Scale 效果。將所有效果顏色值轉換為相對於其亮度的灰階色調。效果的 alpha（opacity）值不受影響。 |
| [HSL](./hsl) | 表示 Hue/Saturation/Luminance 效果。色相、飽和度與亮度皆可相對於目前值進行調整。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | 不可變物件，表示只讀的有效圖像變換效果集合。 |
| [ImageTransformOperation](./imagetransformoperation) | 表示抽象的圖像變換效果。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | 表示套用於圖像的效果集合。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | 允許建立圖像變換操作 |
| [InnerShadow](./innershadow) | 表示 Inner Shadow 效果。 |
| [Luminance](./luminance) | 表示 Luminance 效果。亮度線性地將所有顏色向白或黑移動。對比度則將所有顏色的差距放大或縮小。 |
| [OuterShadow](./outershadow) | 表示 Outer Shadow 效果。 |
| [PresetShadow](./presetshadow) | 表示 Preset Shadow 效果。 |
| [Reflection](./reflection) | 表示 Reflection 效果。 |
| [SoftEdge](./softedge) | 表示 Soft Edge 效果。圖形的邊緣會被模糊，而填充則不受影響。 |
| [Tint](./tint) | 表示 Tint 效果。根據指定量將效果顏色值向色相方向或相反方向移動。 |

## Interfaces

| 介面 | 說明 |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | 表示 Alpha Bi-Level 效果。Alpha（Opacity）值低於閾值的會被變為 0（完全透明），而大於或等於閾值的 Alpha 值會被變為 100%（完全不透明）。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | 不可變物件，表示 Alpha Bi-Level 效果。Alpha（Opacity）值低於閾值的會被變為 0（完全透明），而大於或等於閾值的 Alpha 值會被變為 100%（完全不透明）。 |
| [IAlphaCeiling](./ialphaceiling) | 表示 Alpha Ceiling 效果。Alpha（opacity）值大於零的會被變為 100%。換句話說，任何部分不透明的物件將變為完全不透明。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | 不可變物件，表示 Alpha Ceiling 效果。Alpha（opacity）值大於零的會被變為 100%。換句話說，任何部分不透明的物件將變為完全不透明。 |
| [IAlphaFloor](./ialphafloor) | 表示 Alpha Floor 效果。Alpha（opacity）值低於 100% 的會被變為 0。換句話說，任何部分透明的物件將變為完全透明。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | 不可變物件，表示 Alpha Floor 效果。Alpha（opacity）值低於 100% 的會被變為 0。換句話說，任何部分透明的物件將變為完全透明。 |
| [IAlphaInverse](./ialphainverse) | 表示 Alpha Inverse 效果。Alpha（opacity）值透過從 100% 減去而反轉。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | 不可變物件，表示 Alpha Inverse 效果。Alpha（opacity）值透過從 100% 減去而反轉。 |
| [IAlphaModulate](./ialphamodulate) | 表示 Alpha Modulate 效果。效果的 alpha（opacity）值會乘以固定的百分比。效果容器指定包含要調變之 alpha 值的效果。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | 不可變物件，表示 Alpha Modulate 效果。效果的 alpha（opacity）值會乘以固定的百分比。效果容器指定包含要調變之 alpha 值的效果。 |
| [IAlphaModulateFixed](./ialphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。效果的 alpha（opacity）值會乘以固定的百分比。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | 不可變物件，表示 Alpha Modulate Fixed 效果。效果的 alpha（opacity）值會乘以固定的百分比。 |
| [IAlphaReplace](./ialphareplace) | 表示基礎 IImageTransformOperation 介面。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | 不可變物件，表示 Alpha Replace 效果。效果的 alpha（opacity）值會被固定的 alpha 所取代。 |
| [IBiLevel](./ibilevel) | 表示基礎 IImageTransformOperation 介面。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | 不可變物件，表示 Bi-Level（黑/白）效果。亮度低於指定閾值的輸入顏色會被變為黑色。亮度大於或等於指定值的輸入顏色會被設定為白色。此效果不會影響 alpha 效果值。 |
| [IBlur](./iblur) | 表示套用於整個圖形（包括填充）的 Blur 效果。所有色彩通道，包括 alpha，皆會受到影響。 |
| [IBlurEffectiveData](./iblureffectivedata) | 不可變物件，表示套用於整個圖形（包括填充）的 Blur 效果。所有色彩通道，包括 alpha，皆會受到影響。 |
| [IBrightnessContrast](./ibrightnesscontrast) | 表示 BrightnessContrast 效果。調整亮度與對比度 |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | 不可變物件，表示 BrightnessContrast 效果。調整亮度與對比度 |
| [IColorChange](./icolorchange) | 表示 Color Change 效果。將 FromColor 的實例取代為 ToColor 的實例。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | 不可變物件，表示 Color Change 效果。將 FromColor 的實例取代為 ToColor 的實例。 |
| [IColorReplace](./icolorreplace) | 表示 Color Replacement 效果。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | 不可變物件，表示 Color Replacement 效果。所有效果顏色會被變更為固定顏色。Alpha 值不受影響。 |
| [IDuotone](./iduotone) | 表示 Duotone 效果。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | 不可變物件，表示 Duotone 效果。對每個像素，透過線性插值將 clr1 與 clr2 結合，以決定該像素的新顏色。 |
| [IEffectEffectiveData](./ieffecteffectivedata) | 抽象不可變物件的基底類別，表示效果。 |
| [IEffectFactory](./ieffectfactory) | 允許建立效果的實例 |
| [IFillOverlay](./ifilloverlay) | 表示 Fill Overlay 效果。可使用填充覆蓋層為物件指定額外的填充，並將兩個填充混合在一起。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | 不可變物件，表示 Fill Overlay 效果。可使用填充覆蓋層為物件指定額外的填充，並將兩個填充混合在一起。 |
| [IGlow](./iglow) | 表示 Glow 效果，會在物件邊緣外加入顏色模糊的輪廓。 |
| [IGlowEffectiveData](./igloweffectivedata) | 不可變物件，表示 Glow 效果，會在物件邊緣外加入顏色模糊的輪廓。 |
| [IGrayScale](./igrayscale) | 表示 IImageTransformOperation 介面。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | 不可變物件，表示 Gray Scale 效果。將所有效果顏色值轉換為相對於其亮度的灰階色調。效果的 alpha（opacity）值不受影響。 |
| [IHSL](./ihsl) | 表示 Hue/Saturation/Luminance 效果。色相、飽和度與亮度皆可相對於目前值進行調整。 |
| [IHSLEffectiveData](./ihsleffectivedata) | 表示 Hue/Saturation/Luminance 效果。色相、飽和度與亮度皆可相對於目前值進行調整。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | 不可變物件，表示只讀的有效圖像變換效果集合。 |
| [IImageTransformOperation](./iimagetransformoperation) | 表示抽象的圖像變換效果。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | 表示套用於圖像的效果集合。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | 允許建立圖像效果的實例 |
| [IInnerShadow](./iinnershadow) | 表示 Inner Shadow 效果。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | 不可變物件，表示 Inner Shadow 效果。 |
| [ILuminance](./iluminance) | 表示 Luminance 效果。亮度線性地將所有顏色向白或黑移動。對比度則將所有顏色的差距放大或縮小。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | 表示 Luminance 效果。亮度線性地將所有顏色向白或黑移動。對比度則將所有顏色的差距放大或縮小。 |
| [IOuterShadow](./ioutershadow) | 表示 Outer Shadow 效果。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | 不可變物件，表示 Outer Shadow 效果。 |
| [IPresetShadow](./ipresetshadow) | 表示 Preset Shadow 效果。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | 不可變物件，表示 Preset Shadow 效果。 |
| [IReflection](./ireflection) | 表示 Reflection 效果。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | 不可變物件，表示 Reflection 效果。 |
| [ISoftEdge](./isoftedge) | 表示 Soft Edge 效果。圖形的邊緣會被模糊，而填充則不受影響。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | 不可變物件，表示 Soft Edge 效果。圖形的邊緣會被模糊，而填充則不受影響。 |
| [ITint](./itint) | 表示 Tint 效果。根據指定量將效果顏色值向色相方向或相反方向移動。 |
| [ITintEffectiveData](./itinteffectivedata) | 不可變物件，表示 Tint 效果。根據指定量將效果顏色值向色相方向或相反方向移動。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->