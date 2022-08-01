---
title: Aspose.Slides.Effects
second_title: Aspose.Slides for .NET API 参考
description: 包含用于在 Microsoft PowerPoint 演示文稿中使用各种效果的类
type: docs
weight: 50
url: /zh/net/aspose.slides.effects/
---
包含用于在 Microsoft PowerPoint 演示文稿中使用各种效果的类。

## 课程

| 班级 | 描述 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | 表示 Alpha Bi-Level 效果。 小于阈值的 Alpha（不透明度）值更改为 0（完全透明）， 大于或等于阈值的 alpha 值更改为 100%（完全不透明）。 |
| [AlphaCeiling](./alphaceiling) | 表示 Alpha Ceiling 效果。 大于零的 Alpha（不透明度）值更改为 100%。 换句话说，任何部分不透明的东西都变成完全不透明的。 |
| [AlphaFloor](./alphafloor) | 表示 Alpha Floor 效果。 小于 100% 的 Alpha（不透明度）值将更改为零。 换句话说，任何部分透明的东西都会变成完全透明的。 |
| [AlphaInverse](./alphainverse) | 表示 Alpha 反转效果。 Alpha（不透明度）值通过从 100% 中减去来反转。 |
| [AlphaModulate](./alphamodulate) | 表示 Alpha 调制效果。 效果 alpha（不透明度）值乘以固定百分比。 效果容器指定包含要调制的 alpha 值的效果。 |
| [AlphaModulateFixed](./alphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。 效果 alpha（不透明度）值乘以固定百分比。 |
| [AlphaReplace](./alphareplace) | 表示和 Alpha 替换效果。 效果 alpha（不透明度）值被固定的 alpha 替换。 |
| [BiLevel](./bilevel) | 表示Bi-Level（黑/白）效果。 亮度小于指定阈值的输入颜色变为黑色。 亮度大于或等于指定值的输入颜色设置为白色。 alpha 效果值不受此效果的影响。 |
| [Blur](./blur) | 表示应用到整个形状的模糊效果，包括其填充。 所有颜色通道，包括 alpha，都会受到影响。 |
| [ColorChange](./colorchange) | 表示颜色变化效果。 FromColor 的实例替换为 ToColor 的实例。 |
| [ColorReplace](./colorreplace) | 表示颜色替换效果。 所有效果颜色都更改为固定颜色。 Alpha 值不受影响。 |
| [Duotone](./duotone) | 表示双色调效果。 对于每个像素，通过线性插值组合 Color1 和 Color2 以确定该像素的新颜色。 |
| [EffectFactory](./effectfactory) | 允许创建效果 |
| [FillOverlay](./filloverlay) | 表示填充叠加效果。填充覆盖可用于为对象指定 附加填充并将这两种填充混合在一起。 |
| [Glow](./glow) | 表示发光效果，其中在对象边缘之外添加了颜色模糊的轮廓 。 |
| [GrayScale](./grayscale) | 表示灰度效果。将所有效果颜色值转换为灰色阴影， 对应于它们的亮度。效果 alpha（不透明度）值不受影响。 |
| [HSL](./hsl) | 表示色相/饱和度/亮度效果。 色相、饱和度和亮度都可以相对于其当前值进行调整。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | 表示有效图像变换效果的只读集合的不可变对象。 |
| [ImageTransformOperation](./imagetransformoperation) | 代表抽象图像变换效果。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | 表示应用于图像的效果集合。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | 允许创建图像变换操作 |
| [InnerShadow](./innershadow) | 表示内阴影效果。 |
| [Luminance](./luminance) | 表示亮度效果。 亮度线性地将所有颜色移近白色或黑色。 对比度将所有颜色缩放为更近或更远。 |
| [OuterShadow](./outershadow) | 表示外阴影效果。 |
| [PresetShadow](./presetshadow) | 表示预设阴影效果。 |
| [Reflection](./reflection) | 表示反射效果。 |
| [SoftEdge](./softedge) | 表示软边缘效果。 形状边缘模糊，而填充不受影响。 |
| [Tint](./tint) | 表示色调效果。 将效果颜色值移向/远离色调指定的量。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | 表示 Alpha Bi-Level 效果。 小于阈值的 Alpha（不透明度）值更改为 0（完全透明）， 大于或等于阈值的 alpha 值更改为 100%（完全不透明）。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | 表示 Alpha 双级效果的不可变对象。 小于阈值的 Alpha（不透明度）值更改为 0（完全透明）， 大于或等于阈值的 alpha 值更改为 100%（完全不透明）。 |
| [IAlphaCeiling](./ialphaceiling) | 表示 Alpha Ceiling 效果。 大于零的 Alpha（不透明度）值更改为 100%。 换句话说，任何部分不透明的东西都变成完全不透明的。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | 表示 Alpha 天花板效果的不可变对象。 大于零的 Alpha（不透明度）值更改为 100%。 换句话说，任何部分不透明的东西都变得完全不透明。 |
| [IAlphaFloor](./ialphafloor) | 表示 Alpha Floor 效果。 小于 100% 的 Alpha（不透明度）值将更改为零。 换句话说，任何部分透明的东西都会变成完全透明的。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | 表示 Alpha Floor 效果的不可变对象。 小于 100% 的 Alpha（不透明度）值将更改为零。 换句话说，任何部分透明的东西都会变成完全透明的。 |
| [IAlphaInverse](./ialphainverse) | 表示 Alpha 反转效果。 Alpha（不透明度）值通过从 100% 中减去来反转。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | 表示 Alpha 反转效果的不可变对象。 Alpha（不透明度）值通过从 100% 中减去来反转。 |
| [IAlphaModulate](./ialphamodulate) | 表示 Alpha 调制效果。 效果 alpha（不透明度）值乘以固定百分比。 效果容器指定包含要调制的 alpha 值的效果。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | 表示 Alpha 调制效果的不可变对象。 效果 alpha（不透明度）值乘以固定百分比。 效果容器指定包含要调制的 alpha 值的效果。 |
| [IAlphaModulateFixed](./ialphamodulatefixed) | 表示 Alpha Modulate Fixed 效果。 效果 alpha（不透明度）值乘以固定百分比。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | 表示 Alpha 调制固定效果的不可变对象。 效果 alpha（不透明度）值乘以固定百分比。 |
| [IAlphaReplace](./ialphareplace) | 表示基本 IImageTransformOperation 接口。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | 表示和 Alpha 替换效果的不可变对象。 效果 alpha（不透明度）值被固定的 alpha 替换。 |
| [IBiLevel](./ibilevel) | 表示基本 IImageTransformOperation 接口。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | 表示双电平（黑/白）效果的不可变对象。 将亮度小于指定阈值的输入颜色更改为黑色。 将亮度大于或等于指定值的输入颜色设置为白色. alpha 效果值不受此效果的影响。 |
| [IBlur](./iblur) | 表示应用到整个形状的模糊效果，包括其填充。 所有颜色通道，包括 alpha，都会受到影响。 |
| [IBlurEffectiveData](./iblureffectivedata) | 表示应用到整个形状（包括其填充）的模糊效果的不可变对象。 包括 alpha 在内的所有颜色通道都会受到影响。 |
| [IColorChange](./icolorchange) | 表示颜色变化效果。 FromColor 的实例替换为 ToColor 的实例。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | 表示颜色变化效果的不可变对象。 FromColor 的实例被 ToColor 的实例替换。 |
| [IColorReplace](./icolorreplace) | 表示颜色替换效果。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | 表示颜色替换效果的不可变对象。 所有效果颜色都更改为固定颜色。 Alpha 值不受影响。 |
| [IDuotone](./iduotone) | 表示双色调效果。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | 表示双色调效果的不可变对象。 对于每个像素，通过线性插值组合 clr1 和 clr2 以确定该像素的新颜色。 |
| [IEffectEffectiveData](./ieffecteffectivedata) | 不可变对象的基类，代表效果。 |
| [IEffectFactory](./ieffectfactory) | 允许创建效果实例 |
| [IFillOverlay](./ifilloverlay) | 表示填充叠加效果。填充覆盖可用于为对象指定 附加填充并将这两种填充混合在一起。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | 表示填充叠加效果的不可变对象。填充覆盖可用于为对象指定 附加填充并将这两种填充混合在一起。 |
| [IGlow](./iglow) | 表示发光效果，其中在对象边缘之外添加了颜色模糊的轮廓 。 |
| [IGlowEffectiveData](./igloweffectivedata) | 表示发光效果的不可变对象，其中在对象边缘之外添加了颜色模糊的轮廓 。 |
| [IGrayScale](./igrayscale) | 代表IImageTransformOperation接口。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | 代表灰度效果的不可变对象。将所有效果颜色值转换为灰色阴影， 对应于它们的亮度。效果 alpha（不透明度）值不受影响。 |
| [IHSL](./ihsl) | 表示色相/饱和度/亮度效果。 色相、饱和度和亮度都可以相对于其当前值进行调整。 |
| [IHSLEffectiveData](./ihsleffectivedata) | 表示色相/饱和度/亮度效果。 色相、饱和度和亮度都可以相对于其当前值进行调整。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | 表示有效图像变换效果的只读集合的不可变对象。 |
| [IImageTransformOperation](./iimagetransformoperation) | 代表抽象图像变换效果。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | 表示应用于图像的效果集合。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | 允许创建图像效果的实例 |
| [IInnerShadow](./iinnershadow) | 表示内阴影效果。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | 表示内部阴影效果的不可变对象。 |
| [ILuminance](./iluminance) | 表示亮度效果。 亮度线性地将所有颜色移近白色或黑色。 对比度将所有颜色缩放为更近或更远。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | 表示亮度效果。 亮度线性地将所有颜色移近白色或黑色。 对比度将所有颜色缩放为更近或更远。 |
| [IOuterShadow](./ioutershadow) | 表示外阴影效果。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | 代表外阴影效果的不可变对象。 |
| [IPresetShadow](./ipresetshadow) | 表示预设阴影效果。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | 代表预设阴影效果的不可变对象。 |
| [IReflection](./ireflection) | 表示反射效果。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | 代表反射效果的不可变对象。 |
| [ISoftEdge](./isoftedge) | 表示软边缘效果。 形状边缘模糊，而填充不受影响。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | 代表软边缘效果的不可变对象。 形状边缘模糊，而填充不受影响。 |
| [ITint](./itint) | 表示色调效果。 将效果颜色值移向/远离色调指定的量。 |
| [ITintEffectiveData](./itinteffectivedata) | 表示色调效果的不可变对象。 将效果颜色值移向/远离色调指定的量。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
