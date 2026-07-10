---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个应用于图像的效果集合。
type: docs
url: /zh/com.aspose.slides/imagetransformoperationcollection/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已实现的接口:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

表示应用于图像的效果集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | 从集合中按索引返回一个 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中指定索引位置移除图像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 将新的 Alpha Bi-Level 效果添加到集合的末尾。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 将新的 Alpha Ceiling 效果添加到集合的末尾。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 将新的 Alpha Floor 效果添加到集合的末尾。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 将新的 Alpha Inverse 效果添加到集合的末尾。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 将新的 Alpha Modulate 效果添加到集合的末尾。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 将新的 Alpha Modulate Fixed 效果添加到集合的末尾。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 将新的 Alpha Replace 效果添加到集合的末尾。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 将新的 Bi-Level (black/white) 效果添加到集合的末尾。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 将新的 Blur 效果添加到集合的末尾。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 将新的 Color Change 效果添加到集合的末尾。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 将新的 Color Replacement 效果添加到集合的末尾。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 将新的 Duotone 效果添加到集合的末尾。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 将新的 Fill Overlay 效果添加到集合的末尾。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 将新的 Gray Scale 效果添加到集合的末尾。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 将新的 Hue/Saturation/Luminance 效果添加到集合的末尾。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 将新的 Luminance 效果添加到集合的末尾。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 将新的 Tint 效果添加到集合的末尾。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 将新的 BrightnessContrast 效果添加到集合的末尾。 |
| [size()](#size--) | 返回集合中图像效果的数量。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 将新的图像效果添加到集合的末尾。 |
| [clear()](#clear--) | 从集合中移除所有图像效果。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组，起始于指定的数组索引。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一个特定对象的出现。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回值:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

从集合中按索引返回一个 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回值:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 对象。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中指定索引位置移除图像效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的图像效果的索引。 |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

将新的 Alpha Bi-Level 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的阈值。 |

**返回值:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 新图像效果在集合中的索引。
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

将新的 Alpha Ceiling 效果添加到集合的末尾。

**返回值:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 新图像效果在集合中的索引。
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

将新的 Alpha Floor 效果添加到集合的末尾。

**返回值:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 新图像效果在集合中的索引。
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

将新的 Alpha Inverse 效果添加到集合的末尾。

**返回值:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 新图像效果在集合中的索引。
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

将新的 Alpha Modulate 效果添加到集合的末尾。

**返回值:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 新图像效果在集合中的索引。
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

将新的 Alpha Modulate Fixed 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| amount | float | 用于缩放 alpha 的百分比。 |

**返回值:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 新图像效果在集合中的索引。
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

将新的 Alpha Replace 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**返回值:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 新图像效果在集合中的索引。
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

将新的 Bi-Level (black/white) 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度阈值。大于等于阈值的设为白色，小于阈值的设为黑色。 |

**返回值:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 新图像效果在集合中的索引。
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

将新的 Blur 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 模糊半径。 |
| grow | boolean | 指定对象的边界是否因模糊而增大。true 表示边界增大，false 表示不增大。 |

**返回值:**
[IBlur](../../com.aspose.slides/iblur) - 新图像效果在集合中的索引。
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

将新的 Color Change 效果添加到集合的末尾。

**返回值:**
[IColorChange](../../com.aspose.slides/icolorchange) - 新图像效果在集合中的索引。
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

将新的 Color Replacement 效果添加到集合的末尾。

**返回值:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 新图像效果在集合中的索引。
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

将新的 Duotone 效果添加到集合的末尾。

**返回值:**
[IDuotone](../../com.aspose.slides/iduotone) - 新图像效果在集合中的索引。
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

将新的 Fill Overlay 效果添加到集合的末尾。

**返回值:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 新图像效果在集合中的索引。
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

将新的 Gray Scale 效果添加到集合的末尾。

**返回值:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 新图像效果在集合中的索引。
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

将新的 Hue/Saturation/Luminance 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 调整色相的度数。 |
| saturation | float | 调整饱和度的百分比。 |
| luminance | float | 调整亮度的百分比。 |

**返回值:**
[IHSL](../../com.aspose.slides/ihsl) - 新图像效果在集合中的索引。
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

将新的 Luminance 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 亮度的百分比。 |
| contrast | float | 对比度的百分比。 |

**返回值:**
[ILuminance](../../com.aspose.slides/iluminance) - 新图像效果在集合中的索引。
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

将新的 Tint 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 要着色的色相。 |
| amount | float | 指定颜色值的偏移量。 |

**返回值:**
[ITint](../../com.aspose.slides/itint) - 新图像效果在集合中的索引。
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

将新的 BrightnessContrast 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 亮度的百分比。 |
| contrast | float | 对比度的百分比。 |

**返回值:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 新图像效果在集合中的索引。
### size() {#size--}
```
public final int size()
```

返回集合中图像效果的数量。只读 int 。

**返回值:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。只读 boolean。

**返回值:**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

将新的图像效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要添加到集合末尾的图像效果。 |
### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有图像效果。
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回值:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 则为 true；否则为 false。
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组，起始于指定的数组索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | 目标数组，一维数组，用于接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的零基数组索引。 |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的对象。 |

**返回值:**
boolean - 如果成功从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 则为 true；否则为 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item 也返回 false。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 用于整个集合的 java.util.Iterator。