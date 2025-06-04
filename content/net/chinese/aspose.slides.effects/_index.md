---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes for .NET API Reference
description: 包含用于处理 Microsoft PowerPoint 演示文稿中各种效果的类。
type: docs
weight: 50
url: /zh/aspose.slides.effects/
---

包含用于处理 Microsoft PowerPoint 演示文稿中各种效果的类。

## 类

| 类 | 描述 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | 表示 Alpha Bi-Level 效果。小于阈值的 Alpha（不透明度）值被更改为 0（完全透明），大于或等于阈值的 alpha 值被更改为 100%（完全不透明）。 |
| [AlphaCeiling](./alphaceiling) | 表示 Alpha Ceiling 效果。大于零的 Alpha（不透明度）值被更改为 100%。换句话说，任何部分不透明的内容都变为完全不透明。 |
| [AlphaFloor](./alphafloor) | 表示 Alpha Floor 效果。小于 100% 的 Alpha（不透明度）值被更改为零。换句话说，任何部分透明的内容都变为完全透明。 |
| [AlphaInverse](./alphainverse) | 表示 Alpha Inverse 效果。通过从 100% 中减去，反转 Alpha（不透明度）值。 |
| [AlphaModulate](./alphamodulate) | 表示 Alpha Modulate 效果。将效果 alpha（不透明度）值乘以固定百分比。效果容器指定包含用于调节的 alpha 值的效果。 |
| [AlphaModulateFixed](./alphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。将效果 alpha（不透明度）值乘以固定百分比。 |
| [AlphaReplace](./alphareplace) | 表示 Alpha Replace 效果。效果 alpha（不透明度）值被固定 alpha 替换。 |
| [BiLevel](./bilevel) | 表示 Bi-Level（黑/白）效果。输入颜色的亮度小于指定阈值被更改为黑色。输入颜色的亮度大于或等于指定值被设置为白色。该效果的 alpha 值不受影响。 |
| [Blur](./blur) | 表示应用于整个形状的模糊效果，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [ColorChange](./colorchange) | 表示颜色变化效果。FromColor 的实例被 ToColor 的实例替换。 |
| [ColorReplace](./colorreplace) | 表示颜色替换效果。所有效果颜色更改为固定颜色。Alpha 值不受影响。 |
| [Duotone](./duotone) | 表示 Duotone 效果。对于每个像素，通过线性插值结合 Color1 和 Color2，以确定该像素的新颜色。 |
| [EffectFactory](./effectfactory) | 允许创建效果 |
| [FillOverlay](./filloverlay) | 表示填充覆盖效果。可以使用填充覆盖指定对象的附加填充，并将两种填充混合在一起。 |
| [Glow](./glow) | 表示发光效果，其中在物体的边缘外部添加一个模糊的轮廓颜色。 |
| [GrayScale](./grayscale) | 表示灰度效果。将所有效果颜色值转换为与其亮度相对应的灰色阴影。效果的 alpha（不透明度）值不受影响。 |
| [HSL](./hsl) | 表示色调/饱和度/亮度效果。色调、饱和度和亮度可以相对于其当前值进行调整。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | 不可变对象，代表只读的有效图像变换效果集合。 |
| [ImageTransformOperation](./imagetransformoperation) | 表示抽象图像转换效果。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | 表示应用于图像的效果集合。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | 允许创建图像变换操作 |
| [InnerShadow](./innershadow) | 表示内阴影效果。 |
| [Luminance](./luminance) | 表示亮度效果。亮度线性地将所有颜色向白色或黑色靠近。对比度缩放所有颜色，使其更靠近或更远离。 |
| [OuterShadow](./outershadow) | 表示外阴影效果。 |
| [PresetShadow](./presetshadow) | 表示预设阴影效果。 |
| [Reflection](./reflection) | 表示反射效果。 |
| [SoftEdge](./softedge) | 表示软边缘效果。形状的边缘被模糊，而填充不受影响。 |
| [Tint](./tint) | 表示色调效果。根据指定的数值，将效果颜色值向色调方向移动/远离。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | 表示 Alpha Bi-Level 效果。小于阈值的 Alpha（不透明度）值被更改为 0（完全透明），大于或等于阈值的 alpha 值被更改为 100%（完全不透明）。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | 不可变对象，表示 Alpha Bi-Level 效果。小于阈值的 Alpha（不透明度）值被更改为 0（完全透明），大于或等于阈值的 alpha 值被更改为 100%（完全不透明）。 |
| [IAlphaCeiling](./ialphaceiling) | 表示 Alpha Ceiling 效果。大于零的 Alpha（不透明度）值被更改为 100%。换句话说，任何部分不透明的内容都变为完全不透明。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | 不可变对象，表示 Alpha Ceiling 效果。大于零的 Alpha（不透明度）值被更改为 100%。换句话说，任何部分不透明的内容都变为完全不透明。 |
| [IAlphaFloor](./ialphafloor) | 表示 Alpha Floor 效果。小于 100% 的 Alpha（不透明度）值被更改为零。换句话说，任何部分透明的内容都变为完全透明。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | 不可变对象，表示 Alpha Floor 效果。小于 100% 的 Alpha（不透明度）值被更改为零。换句话说，任何部分透明的内容都变为完全透明。 |
| [IAlphaInverse](./ialphainverse) | 表示 Alpha Inverse 效果。通过从 100% 中减去，反转 Alpha（不透明度）值。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | 不可变对象，表示 Alpha Inverse 效果。通过从 100% 中减去，反转 Alpha（不透明度）值。 |
| [IAlphaModulate](./ialphamodulate) | 表示 Alpha Modulate 效果。将效果 alpha（不透明度）值乘以固定百分比。效果容器指定包含用于调节的 alpha 值的效果。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | 不可变对象，表示 Alpha Modulate 效果。将效果 alpha（不透明度）值乘以固定百分比。效果容器指定包含用于调节的 alpha 值的效果。 |
| [IAlphaModulateFixed](./ialphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。将效果 alpha（不透明度）值乘以固定百分比。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | 不可变对象，表示 Alpha Modulate Fixed 效果。将效果 alpha（不透明度）值乘以固定百分比。 |
| [IAlphaReplace](./ialphareplace) | 表示基本 IImageTransformOperation 接口。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | 不可变对象，表示 Alpha Replace 效果。效果 alpha（不透明度）值被固定 alpha 替换。 |
| [IBiLevel](./ibilevel) | 表示基本 IImageTransformOperation 接口。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | 不可变对象，表示 Bi-Level（黑/白）效果。输入颜色的亮度小于指定阈值被更改为黑色。输入颜色的亮度大于或等于指定值被设置为白色。该效果的 alpha 值不受影响。 |
| [IBlur](./iblur) | 表示应用于整个形状的模糊效果，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [IBlurEffectiveData](./iblureffectivedata) | 不可变对象，表示应用于整个形状的模糊效果，包括其填充。所有颜色通道，包括 alpha，都受到影响。 |
| [IColorChange](./icolorchange) | 表示颜色变化效果。FromColor 的实例被 ToColor 的实例替换。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | 不可变对象，表示颜色变化效果。FromColor 的实例被 ToColor 的实例替换。 |
| [IColorReplace](./icolorreplace) | 表示颜色替换效果。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | 不可变对象，表示颜色替换效果。所有效果颜色更改为固定颜色。Alpha 值不受影响。 |
| [IDuotone](./iduotone) | 表示 Duotone 效果。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | 不可变对象，表示 Duotone 效果。对于每个像素，通过线性插值结合 clr1 和 clr2，以确定该像素的新颜色。 |
| [IEffectEffectiveData](./ieffecteffectivedata) | 代表效果的不可变对象的基类。 |
| [IEffectFactory](./ieffectfactory) | 允许创建效果实例 |
| [IFillOverlay](./ifilloverlay) | 表示填充覆盖效果。可以使用填充覆盖指定对象的附加填充，并将两种填充混合在一起。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | 不可变对象，表示填充覆盖效果。可以使用填充覆盖指定对象的附加填充，并将两种填充混合在一起。 |
| [IGlow](./iglow) | 表示发光效果，其中在物体的边缘外部添加一个模糊的轮廓颜色。 |
| [IGlowEffectiveData](./igloweffectivedata) | 不可变对象，表示发光效果，其中在物体的边缘外部添加一个模糊的轮廓颜色。 |
| [IGrayScale](./igrayscale) | 表示 IImageTransformOperation 接口。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | 不可变对象，表示灰度效果。将所有效果颜色值转换为与其亮度相对应的灰色阴影。效果的 alpha（不透明度）值不受影响。 |
| [IHSL](./ihsl) | 表示色调/饱和度/亮度效果。色调、饱和度和亮度可以相对于其当前值进行调整。 |
| [IHSLEffectiveData](./ihsleffectivedata) | 表示色调/饱和度/亮度效果。色调、饱和度和亮度可以相对于其当前值进行调整。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | 不可变对象，代表只读的有效图像变换效果集合。 |
| [IImageTransformOperation](./iimagetransformoperation) | 表示抽象图像转换效果。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | 表示应用于图像的效果集合。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | 允许创建图像效果实例 |
| [IInnerShadow](./iinnershadow) | 表示内阴影效果。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | 不可变对象，表示内阴影效果。 |
| [ILuminance](./iluminance) | 表示亮度效果。亮度线性地将所有颜色向白色或黑色靠近。对比度缩放所有颜色，使其更靠近或更远离。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | 表示亮度效果。亮度线性地将所有颜色向白色或黑色靠近。对比度缩放所有颜色，使其更靠近或更远离。 |
| [IOuterShadow](./ioutershadow) | 表示外阴影效果。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | 不可变对象，表示外阴影效果。 |
| [IPresetShadow](./ipresetshadow) | 表示预设阴影效果。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | 不可变对象，表示预设阴影效果。 |
| [IReflection](./ireflection) | 表示反射效果。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | 不可变对象，表示反射效果。 |
| [ISoftEdge](./isoftedge) | 表示软边缘效果。形状的边缘被模糊，而填充不受影响。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | 不可变对象，表示软边缘效果。形状的边缘被模糊，而填充不受影响。 |
| [ITint](./itint) | 表示色调效果。根据指定的数值，将效果颜色值向色调方向移动/远离。 |
| [ITintEffectiveData](./itinteffectivedata) | 不可变对象，表示色调效果。根据指定的数值，将效果颜色值向色调方向移动/远离。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->