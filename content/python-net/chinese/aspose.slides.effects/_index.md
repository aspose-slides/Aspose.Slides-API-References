---
title: aspose.slides.effects
second_title: Aspose.Slides .NET API（通过 Python）参考
description: 
type: docs
url: /zh/aspose.slides.effects/
---
包含用于处理 Microsoft PowerPoint 演示文稿中各种效果的类。
## 类

| 类 | 描述 |
| :- | :- |
| [`AlphaBiLevel`](/slides/python-net/zh/aspose.slides.effects/alphabilevel/) | 表示 Alpha 双层效果。<br/>            Alpha（不透明度）值小于阈值的将被改为 0（完全透明），<br/>            大于或等于阈值的 alpha 值将被改为 100%（完全不透明）。 |
| [`AlphaCeiling`](/slides/python-net/zh/aspose.slides.effects/alphaceiling/) | 表示 Alpha 上限效果。<br/>            Alpha（不透明度）值大于零的将被改为 100%。<br/>            换句话说，所有部分不透明的对象将变为完全不透明。 |
| [`AlphaFloor`](/slides/python-net/zh/aspose.slides.effects/alphafloor/) | 表示 Alpha 下限效果。<br/>            Alpha（不透明度）值小于 100% 的将被改为零。<br/>            换句话说，所有部分透明的对象将变为完全透明。 |
| [`AlphaInverse`](/slides/python-net/zh/aspose.slides.effects/alphainverse/) | 表示 Alpha 反转效果。<br/>            Alpha（不透明度）值通过从 100% 减去来进行反转。 |
| [`AlphaModulate`](/slides/python-net/zh/aspose.slides.effects/alphamodulate/) | 表示 Alpha 调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。<br/>            效果容器指定一个包含需要调制的 alpha 值的效果。 |
| [`AlphaModulateFixed`](/slides/python-net/zh/aspose.slides.effects/alphamodulatefixed/) | 表示 Alpha 固定调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。 |
| [`AlphaReplace`](/slides/python-net/zh/aspose.slides.effects/alphareplace/) | 表示 Alpha 替换效果。<br/>            效果的 alpha（不透明度）值被固定的 alpha 替代。 |
| [`BiLevel`](/slides/python-net/zh/aspose.slides.effects/bilevel/) | 表示双层（黑/白）效果。<br/>            亮度低于指定阈值的输入颜色将被改为黑色。<br/>            亮度大于或等于指定值的输入颜色将被设为白色。<br/>            此效果不会影响 alpha 效果值。 |
| [`Blur`](/slides/python-net/zh/aspose.slides.effects/blur/) | 表示对整个形状（包括填充）应用的模糊效果。<br/>            所有颜色通道，包括 alpha，均受到影响。 |
| [`BrightnessContrast`](/slides/python-net/zh/aspose.slides.effects/brightnesscontrast/) | 表示亮度对比度效果。<br/>            调整亮度和对比度 |
| [`ColorChange`](/slides/python-net/zh/aspose.slides.effects/colorchange/) | 表示颜色更改效果。<br/>            将 FromColor 实例替换为 ToColor 实例。 |
| [`ColorReplace`](/slides/python-net/zh/aspose.slides.effects/colorreplace/) | 表示颜色替换效果。<br/>            所有效果颜色均被更改为固定颜色。<br/>            Alpha 值不受影响。 |
| [`Duotone`](/slides/python-net/zh/aspose.slides.effects/duotone/) | 表示双音调效果。<br/>            对每个像素，通过线性插值将 Color1 与 Color2 组合，<br/>            以确定该像素的新颜色。 |
| [`EffectFactory`](/slides/python-net/zh/aspose.slides.effects/effectfactory/) | 允许创建效果 |
| [`FillOverlay`](/slides/python-net/zh/aspose.slides.effects/filloverlay/) | 表示填充覆盖效果。填充覆盖可用于指定<br/>            对象的额外填充，并将两个填充混合在一起。 |
| [`Glow`](/slides/python-net/zh/aspose.slides.effects/glow/) | 表示辉光效果，在对象边缘之外添加彩色模糊轮廓 <br/>            。 |
| [`GrayScale`](/slides/python-net/zh/aspose.slides.effects/grayscale/) | 表示灰度效果。将所有效果颜色值转换为对应其亮度的灰色调，<br/>            效果的 alpha（不透明度）值不受影响。 |
| [`HSL`](/slides/python-net/zh/aspose.slides.effects/hsl/) | 表示色相/饱和度/亮度效果。<br/>            色相、饱和度和亮度均可相对于当前值进行调整。 |
| [`IAlphaBiLevel`](/slides/python-net/zh/aspose.slides.effects/ialphabilevel/) | 表示 Alpha 双层效果。<br/>            Alpha（不透明度）值小于阈值的将被改为 0（完全透明），<br/>            大于或等于阈值的 alpha 值将被改为 100%（完全不透明）。 |
| [`IAlphaBiLevelEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphabileveleffectivedata/) | 不可变对象，表示 Alpha 双层效果。<br/>            Alpha（不透明度）值小于阈值的将被改为 0（完全透明），<br/>            大于或等于阈值的 alpha 值将被改为 100%（完全不透明）。 |
| [`IAlphaCeiling`](/slides/python-net/zh/aspose.slides.effects/ialphaceiling/) | 表示 Alpha 上限效果。<br/>            Alpha（不透明度）值大于零的将被改为 100%。<br/>            换句话说，所有部分不透明的对象将变为完全不透明。 |
| [`IAlphaCeilingEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphaceilingeffectivedata/) | 不可变对象，表示 Alpha 上限效果。<br/>            Alpha（不透明度）值大于零的将被改为 100%。<br/>            换句话说，所有部分不透明的对象将变为完全不透明。 |
| [`IAlphaFloor`](/slides/python-net/zh/aspose.slides.effects/ialphafloor/) | 表示 Alpha 下限效果。<br/>            Alpha（不透明度）值小于 100% 的将被改为零。<br/>            换句话说，所有部分透明的对象将变为完全透明。 |
| [`IAlphaFloorEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphaflooreffectivedata/) | 不可变对象，表示 Alpha 下限效果。<br/>            Alpha（不透明度）值小于 100% 的将被改为零。<br/>            换句话说，所有部分透明的对象将变为完全透明。 |
| [`IAlphaInverse`](/slides/python-net/zh/aspose.slides.effects/ialphainverse/) | 表示 Alpha 反转效果。<br/>            Alpha（不透明度）值通过从 100% 减去来进行反转。 |
| [`IAlphaInverseEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphainverseeffectivedata/) | 不可变对象，表示 Alpha 反转效果。<br/>            Alpha（不透明度）值通过从 100% 减去来进行反转。 |
| [`IAlphaModulate`](/slides/python-net/zh/aspose.slides.effects/ialphamodulate/) | 表示 Alpha 调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。<br/>            效果容器指定一个包含 alpha 值的效果以进行调制。 |
| [`IAlphaModulateEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphamodulateeffectivedata/) | 不可变对象，表示 Alpha 调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。<br/>            效果容器指定一个包含 alpha 值的效果以进行调制。 |
| [`IAlphaModulateFixed`](/slides/python-net/zh/aspose.slides.effects/ialphamodulatefixed/) | 表示 Alpha 固定调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。 |
| [`IAlphaModulateFixedEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphamodulatefixedeffectivedata/) | 不可变对象，表示 Alpha 固定调制效果。<br/>            效果的 alpha（不透明度）值乘以固定的百分比。 |
| [`IAlphaReplace`](/slides/python-net/zh/aspose.slides.effects/ialphareplace/) | 表示基础 IImageTransformOperation 接口。 |
| [`IAlphaReplaceEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ialphareplaceeffectivedata/) | 不可变对象，表示 Alpha 替换效果。<br/>            效果的 alpha（不透明度）值被固定的 alpha 替代。 |
| [`IBiLevel`](/slides/python-net/zh/aspose.slides.effects/ibilevel/) | 表示基础 IImageTransformOperation 接口。 |
| [`IBiLevelEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ibileveleffectivedata/) | 不可变对象，表示双层（黑/白）效果。<br/>            亮度低于指定阈值的输入颜色将被改为黑色。<br/>            亮度大于或等于指定值的输入颜色将被设为白色。<br/>            此效果不会影响 alpha 效果值。 |
| [`IBlur`](/slides/python-net/zh/aspose.slides.effects/iblur/) | 表示对整个形状（包括填充）应用的模糊效果。<br/>            所有颜色通道，包括 alpha，均受到影响。 |
| [`IBlurEffectiveData`](/slides/python-net/zh/aspose.slides.effects/iblureffectivedata/) | 不可变对象，表示对整个形状（包括填充）应用的模糊效果。<br/>            所有颜色通道，包括 alpha，均受到影响。 |
| [`IBrightnessContrast`](/slides/python-net/zh/aspose.slides.effects/ibrightnesscontrast/) | 表示亮度对比度效果。<br/>            调整亮度和对比度 |
| [`IBrightnessContrastEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ibrightnesscontrasteffectivedata/) | 不可变对象，表示亮度对比度效果。<br/>            调整亮度和对比度 |
| [`IColorChange`](/slides/python-net/zh/aspose.slides.effects/icolorchange/) | 表示颜色更改效果。<br/>            将 FromColor 实例替换为 ToColor 实例。 |
| [`IColorChangeEffectiveData`](/slides/python-net/zh/aspose.slides.effects/icolorchangeeffectivedata/) | 不可变对象，表示颜色更改效果。<br/>            将 FromColor 实例替换为 ToColor 实例。 |
| [`IColorReplace`](/slides/python-net/zh/aspose.slides.effects/icolorreplace/) | 表示颜色替换效果。 |
| [`IColorReplaceEffectiveData`](/slides/python-net/zh/aspose.slides.effects/icolorreplaceeffectivedata/) | 不可变对象，表示颜色替换效果。<br/>            所有效果颜色均被更改为固定颜色。<br/>            Alpha 值不受影响。 |
| [`IDuotone`](/slides/python-net/zh/aspose.slides.effects/iduotone/) | 表示双音调效果。 |
| [`IDuotoneEffectiveData`](/slides/python-net/zh/aspose.slides.effects/iduotoneeffectivedata/) | 不可变对象，表示双音调效果。<br/>            对每个像素，通过线性插值将 clr1 与 clr2 组合，<br/>            以确定该像素的新颜色。 |
| [`IEffectEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ieffecteffectivedata/) | 不可变对象的基类，表示效果。 |
| [`IEffectFactory`](/slides/python-net/zh/aspose.slides.effects/ieffectfactory/) | 允许创建效果实例 |
| [`IFillOverlay`](/slides/python-net/zh/aspose.slides.effects/ifilloverlay/) | 表示填充覆盖效果。填充覆盖可用于指定<br/>            对象的额外填充，并将两个填充混合在一起。 |
| [`IFillOverlayEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ifilloverlayeffectivedata/) | 不可变对象，表示填充覆盖效果。填充覆盖可用于指定<br/>            对象的额外填充，并将两个填充混合在一起。 |
| [`IGlow`](/slides/python-net/zh/aspose.slides.effects/iglow/) | 表示辉光效果，在对象边缘之外添加彩色模糊轮廓 <br/>            。 |
| [`IGlowEffectiveData`](/slides/python-net/zh/aspose.slides.effects/igloweffectivedata/) | 不可变对象，表示辉光效果，在对象边缘之外添加彩色模糊轮廓 <br/>            。 |
| [`IGrayScale`](/slides/python-net/zh/aspose.slides.effects/igrayscale/) | 表示 IImageTransformOperation 接口。 |
| [`IGrayScaleEffectiveData`](/slides/python-net/zh/aspose.slides.effects/igrayscaleeffectivedata/) | 不可变对象，表示灰度效果。将所有效果颜色值转换为对应其亮度的灰色调，<br/>            效果的 alpha（不透明度）值不受影响。 |
| [`IHSL`](/slides/python-net/zh/aspose.slides.effects/ihsl/) | 表示色相/饱和度/亮度效果。<br/>            色相、饱和度和亮度均可相对于当前值进行调整。 |
| [`IHSLEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ihsleffectivedata/) | 表示色相/饱和度/亮度效果。<br/>            色相、饱和度和亮度均可相对于当前值进行调整。 |
| [`IImageTransformOCollectionEffectiveData`](/slides/python-net/zh/aspose.slides.effects/iimagetransformocollectioneffectivedata/) | 不可变对象，表示只读的有效图像转换效果集合。 |
| [`IImageTransformOperation`](/slides/python-net/zh/aspose.slides.effects/iimagetransformoperation/) | 表示抽象的图像转换效果。 |
| [`IImageTransformOperationCollection`](/slides/python-net/zh/aspose.slides.effects/iimagetransformoperationcollection/) | 表示应用于图像的效果集合。 |
| [`IImageTransformOperationFactory`](/slides/python-net/zh/aspose.slides.effects/iimagetransformoperationfactory/) | 允许创建图像效果实例 |
| [`IInnerShadow`](/slides/python-net/zh/aspose.slides.effects/iinnershadow/) | 表示内部阴影效果。 |
| [`IInnerShadowEffectiveData`](/slides/python-net/zh/aspose.slides.effects/iinnershadoweffectivedata/) | 不可变对象，表示内部阴影效果。 |
| [`ILuminance`](/slides/python-net/zh/aspose.slides.effects/iluminance/) | 表示亮度效果。<br/>            亮度线性地将所有颜色向更亮或更暗的方向移动。<br/>            对比度对所有颜色进行缩放，使其更接近或更远离。 |
| [`ILuminanceEffectiveData`](/slides/python-net/zh/aspose.slides.effects/iluminanceeffectivedata/) | 表示亮度效果。<br/>            亮度线性地将所有颜色向更亮或更暗的方向移动。<br/>            对比度对所有颜色进行缩放，使其更接近或更远离。 |
| [`IOuterShadow`](/slides/python-net/zh/aspose.slides.effects/ioutershadow/) | 表示外部阴影效果。 |
| [`IOuterShadowEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ioutershadoweffectivedata/) | 不可变对象，表示外部阴影效果。 |
| [`IPresetShadow`](/slides/python-net/zh/aspose.slides.effects/ipresetshadow/) | 表示预设阴影效果。 |
| [`IPresetShadowEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ipresetshadoweffectivedata/) | 不可变对象，表示预设阴影效果。 |
| [`IReflection`](/slides/python-net/zh/aspose.slides.effects/ireflection/) | 表示反射效果。 |
| [`IReflectionEffectiveData`](/slides/python-net/zh/aspose.slides.effects/ireflectioneffectivedata/) | 不可变对象，表示反射效果。 |
| [`ISoftEdge`](/slides/python-net/zh/aspose.slides.effects/isoftedge/) | 表示软边缘效果。 <br/>            形状的边缘被模糊，而填充不受影响。 |
| [`ISoftEdgeEffectiveData`](/slides/python-net/zh/aspose.slides.effects/isoftedgeeffectivedata/) | 不可变对象，表示软边缘效果。 <br/>            形状的边缘被模糊，而填充不受影响。 |
| [`ITint`](/slides/python-net/zh/aspose.slides.effects/itint/) | 表示色调效果。<br/>            按指定量将效果颜色值向/远离色相移动。 |
| [`ITintEffectiveData`](/slides/python-net/zh/aspose.slides.effects/itinteffectivedata/) | 不可变对象，表示色调效果。<br/>            按指定量将效果颜色值向/远离色相移动。 |
| [`ImageTransformOCollectionEffectiveData`](/slides/python-net/zh/aspose.slides.effects/imagetransformocollectioneffectivedata/) | 不可变对象，表示只读的有效图像转换效果集合。 |
| [`ImageTransformOperation`](/slides/python-net/zh/aspose.slides.effects/imagetransformoperation/) | 表示抽象的图像转换效果。 |
| [`ImageTransformOperationCollection`](/slides/python-net/zh/aspose.slides.effects/imagetransformoperationcollection/) | 表示应用于图像的效果集合。 |
| [`ImageTransformOperationFactory`](/slides/python-net/zh/aspose.slides.effects/imagetransformoperationfactory/) | 允许创建图像转换操作 |
| [`InnerShadow`](/slides/python-net/zh/aspose.slides.effects/innershadow/) | 表示内部阴影效果。 |
| [`Luminance`](/slides/python-net/zh/aspose.slides.effects/luminance/) | 表示亮度效果。<br/>            亮度线性地将所有颜色向更亮或更暗的方向移动。<br/>            对比度对所有颜色进行缩放，使其更接近或更远离。 |
| [`OuterShadow`](/slides/python-net/zh/aspose.slides.effects/outershadow/) | 表示外部阴影效果。 |
| [`PresetShadow`](/slides/python-net/zh/aspose.slides.effects/presetshadow/) | 表示预设阴影效果。 |
| [`Reflection`](/slides/python-net/zh/aspose.slides.effects/reflection/) | 表示反射效果。 |
| [`SoftEdge`](/slides/python-net/zh/aspose.slides.effects/softedge/) | 表示软边缘效果。 <br/>            形状的边缘被模糊，而填充不受影响。 |
| [`Tint`](/slides/python-net/zh/aspose.slides.effects/tint/) | 表示色调效果。<br/>            按指定量将效果颜色值向/远离色相移动。 |