---
title: "Aspose::Slides::Effects"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 66
url: /zh/aspose.slides.effects/
---
## 类

| 类 | 描述 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel/) | 表示一个 Alpha Bi-Level 效果。Alpha（Opacity）值小于阈值的将被更改为 0（完全透明），大于或等于阈值的将被更改为 100%（完全不透明）。 |
| [AlphaCeiling](./alphaceiling/) | 表示一个 Alpha Ceiling 效果。Alpha（opacity）值大于零的将被更改为 100%。换句话说，任何部分不透明的都会变为完全不透明。 |
| [AlphaFloor](./alphafloor/) | 表示一个 Alpha Floor 效果。Alpha（opacity）值小于 100% 的将被更改为零。换句话说，任何部分透明的都会变为完全透明。 |
| [AlphaInverse](./alphainverse/) | 表示一个 Alpha Inverse 效果。Alpha（opacity）值通过从 100% 中减去而取反。 |
| [AlphaModulate](./alphamodulate/) | 表示一个 Alpha Modulate 效果。Effect alpha（opacity）值乘以固定百分比。效果容器指定一个包含要调制的 alpha 值的效果。 |
| [AlphaModulateFixed](./alphamodulatefixed/) | 表示一个 Alpha Modulate Fixed 效果。Effect alpha（opacity）值乘以固定百分比。 |
| [AlphaReplace](./alphareplace/) | 表示一个 Alpha Replace 效果。Effect alpha（opacity）值被固定的 alpha 替换。 |
| [BiLevel](./bilevel/) | 表示一个 Bi-Level（black/white）效果。亮度小于指定阈值的输入颜色将被更改为黑色。亮度大于或等于指定值的输入颜色将被设为白色。Alpha 效果值不受此效果影响。 |
| [Blur](./blur/) | 表示一个 [Blur](./blur/) 效果，该效果应用于整个形状，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [BrightnessContrast](./brightnesscontrast/) | 表示一个 [BrightnessContrast](./brightnesscontrast/) 效果。调整亮度和对比度 |
| [ColorChange](./colorchange/) | 表示一个 Color Change 效果。FromColor 的实例被 ToColor 的实例替换。 |
| [ColorReplace](./colorreplace/) | 表示一个 Color Replacement 效果。所有效果颜色被更改为固定颜色。Alpha 值不受影响。 |
| [Duotone](./duotone/) | 表示一个 [Duotone](./duotone/) 效果。对于每个像素，通过线性插值将 Color1 和 Color2 合成，以确定该像素的新颜色。 |
| [EffectFactory](./effectfactory/) | 允许创建效果 |
| [FillOverlay](./filloverlay/) | 表示一个 Fill Overlay 效果。填充叠加可用于为对象指定额外的填充，并将两种填充混合在一起。 |
| [Glow](./glow/) | 表示一个 [Glow](./glow/) 效果，其中在对象的边缘之外添加颜色模糊轮廓。 |
| [GrayScale](./grayscale/) | 表示一个 Gray Scale 效果。将所有效果颜色值转换为对应其亮度的灰色阴影。Effect alpha（opacity）值保持不变。 |
| [HSL](./hsl/) | 表示一个 Hue/Saturation/Luminance 效果。色相、饱和度和亮度均可相对于当前值进行调整。 |
| [IAlphaBiLevel](./ialphabilevel/) | 表示一个 Alpha Bi-Level 效果。Alpha（Opacity）值小于阈值的将被更改为 0（完全透明），大于或等于阈值的将被更改为 100%（完全不透明）。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata/) | 不可变对象，表示一个 Alpha Bi-Level 效果。Alpha（Opacity）值小于阈值的将被更改为 0（完全透明），大于或等于阈值的将被更改为 100%（完全不透明）。 |
| [IAlphaCeiling](./ialphaceiling/) | 表示一个 Alpha Ceiling 效果。Alpha（opacity）值大于零的将被更改为 100%。换句话说，任何部分不透明的都会变为完全不透明。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata/) | 不可变对象，表示一个 Alpha Ceiling 效果。Alpha（opacity）值大于零的将被更改为 100%。换句话说，任何部分不透明的都会变为完全不透明。 |
| [IAlphaFloor](./ialphafloor/) | 表示一个 Alpha Floor 效果。Alpha（opacity）值小于 100% 的将被更改为零。换句话说，任何部分透明的都会变为完全透明。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata/) | 不可变对象，表示一个 Alpha Floor 效果。Alpha（opacity）值小于 100% 的将被更改为零。换句话说，任何部分透明的都会变为完全透明。 |
| [IAlphaInverse](./ialphainverse/) | 表示一个 Alpha Inverse 效果。Alpha（opacity）值通过从 100% 中减去而取反。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata/) | 不可变对象，表示一个 Alpha Inverse 效果。Alpha（opacity）值通过从 100% 中减去而取反。 |
| [IAlphaModulate](./ialphamodulate/) | 表示一个 Alpha Modulate 效果。Effect alpha（opacity）值乘以固定百分比。效果容器指定一个包含要调制的 alpha 值的效果。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata/) | 不可变对象，表示一个 Alpha Modulate 效果。Effect alpha（opacity）值乘以固定百分比。效果容器指定一个包含要调制的 alpha 值的效果。 |
| [IAlphaModulateFixed](./ialphamodulatefixed/) | 表示一个 Alpha Modulate Fixed 效果。Effect alpha（opacity）值乘以固定百分比。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata/) | 不可变对象，表示一个 Alpha Modulate Fixed 效果。Effect alpha（opacity）值乘以固定百分比。 |
| [IAlphaReplace](./ialphareplace/) | 表示基础 [IImageTransformOperation](./iimagetransformoperation/) 接口。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata/) | 不可变对象，表示一个 Alpha Replace 效果。Effect alpha（opacity）值被固定的 alpha 替换。 |
| [IApplicableEffect](./iapplicableeffect/) |  |
| [IBiLevel](./ibilevel/) | 表示基础 [IImageTransformOperation](./iimagetransformoperation/) 接口。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata/) | 不可变对象，表示一个 Bi-Level（black/white）效果。亮度小于指定阈值的输入颜色将被更改为黑色。亮度大于或等于指定值的输入颜色将被设为白色。Alpha 效果值不受此效果影响。 |
| [IBlur](./iblur/) | 表示一个 [Blur](./blur/) 效果，该效果应用于整个形状，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [IBlurEffectiveData](./iblureffectivedata/) | 不可变对象，表示一个 [Blur](./blur/) 效果，该效果应用于整个形状，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [IBrightnessContrast](./ibrightnesscontrast/) | 表示一个 [BrightnessContrast](./brightnesscontrast/) 效果。调整亮度和对比度 |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata/) | 不可变对象，表示一个 [BrightnessContrast](./brightnesscontrast/) 效果。调整亮度和对比度 |
| [IColorChange](./icolorchange/) | 表示一个 Color Change 效果。FromColor 的实例被 ToColor 的实例替换。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata/) | 不可变对象，表示一个 Color Change 效果。FromColor 的实例被 ToColor 的实例替换。 |
| [IColorReplace](./icolorreplace/) | 表示一个 Color Replacement 效果。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata/) | 不可变对象，表示一个 Color Replacement 效果。所有效果颜色被更改为固定颜色。Alpha 值不受影响。 |
| [IDuotone](./iduotone/) | 表示一个 [Duotone](./duotone/) 效果。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata/) | 不可变对象，表示一个 [Duotone](./duotone/) 效果。对于每个像素，通过线性插值将 clr1 和 clr2 合成，以确定该像素的新颜色。 |
| [IEffectEffectiveData](./ieffecteffectivedata/) | 不可变对象的基类，表示效果。 |
| [IEffectFactory](./ieffectfactory/) | 允许创建效果实例 |
| [IFillOverlay](./ifilloverlay/) | 表示一个 Fill Overlay 效果。填充叠加可用于为对象指定额外的填充，并将两种填充混合在一起。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata/) | 不可变对象，表示一个 Fill Overlay 效果。填充叠加可用于为对象指定额外的填充，并将两种填充混合在一起。 |
| [IGlow](./iglow/) | 表示一个 [Glow](./glow/) 效果，其中在对象的边缘之外添加颜色模糊轮廓。 |
| [IGlowEffectiveData](./igloweffectivedata/) | 不可变对象，表示一个 [Glow](./glow/) 效果，其中在对象的边缘之外添加颜色模糊轮廓。 |
| [IGrayScale](./igrayscale/) | 表示 [IImageTransformOperation](./iimagetransformoperation/) 接口。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata/) | 不可变对象，表示一个 Gray Scale 效果。将所有效果颜色值转换为对应其亮度的灰色阴影。Effect alpha（opacity）值保持不变。 |
| [IHSL](./ihsl/) | 表示一个 Hue/Saturation/Luminance 效果。色相、饱和度和亮度均可相对于当前值进行调整。 |
| [IHSLEffectiveData](./ihsleffectivedata/) | 表示一个 Hue/Saturation/Luminance 效果。色相、饱和度和亮度均可相对于当前值进行调整。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata/) | 不可变对象，表示有效图像变换效果的只读集合。 |
| [IImageTransformOperation](./iimagetransformoperation/) | 表示抽象图像变换效果。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection/) | 表示应用于图像的效果集合。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory/) | 允许创建图像效果实例 |
| [IInnerShadow](./iinnershadow/) | 表示一个内阴影效果。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata/) | 不可变对象，表示一个内阴影效果。 |
| [ILuminance](./iluminance/) | 表示一个 [Luminance](./luminance/) 效果。亮度线性地将所有颜色向白或黑移动。对比度按比例放大或减小颜色之间的差距。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata/) | 表示一个 [Luminance](./luminance/) 效果。亮度线性地将所有颜色向白或黑移动。对比度按比例放大或减小颜色之间的差距。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata/) | 不可变对象，表示有效图像变换效果的只读集合。 |
| [ImageTransformOperation](./imagetransformoperation/) | 表示抽象图像变换效果。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection/) | 表示应用于图像的效果集合。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory/) | 允许创建图像变换操作 |
| [InnerShadow](./innershadow/) | 表示一个 Inner Shadow 效果。 |
| [IOuterShadow](./ioutershadow/) | 表示一个 Outer Shadow 效果。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata/) | 不可变对象，表示一个 Outer Shadow 效果。 |
| [IPresetShadow](./ipresetshadow/) | 表示一个 Preset Shadow 效果。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata/) | 不可变对象，表示一个 Preset Shadow 效果。 |
| [IReflection](./ireflection/) | 表示一个 reflection 效果。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata/) | 不可变对象，表示一个 [Reflection](./reflection/) 效果。 |
| [ISoftEdge](./isoftedge/) | 表示一个 Soft Edge 效果。形状的边缘被模糊，而填充不受影响。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata/) | 不可变对象，表示一个 soft edge 效果。形状的边缘被模糊，而填充不受影响。 |
| [ITint](./itint/) | 表示一个 [Tint](./tint/) 效果。按指定量将效果颜色值向/远离色相平移。 |
| [ITintEffectiveData](./itinteffectivedata/) | 不可变对象，表示一个 [Tint](./tint/) 效果。按指定量将效果颜色值向/远离色相平移。 |
| [IVisualEffect](./ivisualeffect/) |  |
| [Luminance](./luminance/) | 表示一个 [Luminance](./luminance/) 效果。亮度线性地将所有颜色向白或黑移动。对比度按比例放大或减小颜色之间的差距。 |
| [OuterShadow](./outershadow/) | 表示一个 Outer Shadow 效果。 |
| [PresetShadow](./presetshadow/) | 表示一个 Preset Shadow 效果。 |
| [Reflection](./reflection/) | 表示一个 [Reflection](./reflection/) 效果。 |
| [SoftEdge](./softedge/) | 表示一个 soft edge 效果。形状的边缘被模糊，而填充不受影响。 |
| [Tint](./tint/) | 表示一个 [Tint](./tint/) 效果。按指定量将效果颜色值向/远离色相平移。 |