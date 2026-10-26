---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Java API 参考
description: 表示对图像应用的一组效果。
type: docs
url: /zh/com.aspose.slides/imagetransformoperationcollection/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

表示对图像应用的一组效果。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | 从集合中按索引返回一个 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中在指定索引处移除图像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 在集合末尾添加新的 Alpha Bi-Level 效果。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 在集合末尾添加新的 Alpha Ceiling 效果。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 在集合末尾添加新的 Alpha Floor 效果。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 在集合末尾添加新的 Alpha Inverse 效果。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 在集合末尾添加新的 Alpha Modulate 效果。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 在集合末尾添加新的 Alpha Modulate Fixed 效果。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 在集合末尾添加新的 Alpha Replace 效果。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 在集合末尾添加新的 Bi-Level (black/white) 效果。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 在集合末尾添加新的 Blur 效果。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 在集合末尾添加新的 Color Change 效果。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 在集合末尾添加新的 Color Replacement 效果。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 在集合末尾添加新的 Duotone 效果。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 在集合末尾添加新的 Fill Overlay 效果。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 在集合末尾添加新的 Gray Scale 效果。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 在集合末尾添加新的 Hue/Saturation/Luminance 效果。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 在集合末尾添加新的 Luminance 效果。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 在集合末尾添加新的 Tint 效果。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 在集合末尾添加新的 BrightnessContrast 效果。 |
| [size()](#size--) | 返回集合中图像效果的数量。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否只读。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 在集合末尾添加新的图像效果。 |
| [clear()](#clear--) | 从集合中移除所有图像效果。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 为整个集合返回一个 java 迭代器。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

从集合中按索引返回一个 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 对象。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中在指定索引处移除图像效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的图像效果的索引。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

在集合末尾添加新的 Alpha Bi-Level 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的阈值。 |

**返回：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 新图像效果在集合中的索引。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

在集合末尾添加新的 Alpha Ceiling 效果。

**返回：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 新图像效果在集合中的索引。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

在集合末尾添加新的 Alpha Floor 效果。

**返回：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 新图像效果在集合中的索引。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

在集合末尾添加新的 Alpha Inverse 效果。

**返回：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 新图像效果在集合中的索引。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

在集合末尾添加新的 Alpha Modulate 效果。

**返回：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 新图像效果在集合中的索引。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

在集合末尾添加新的 Alpha Modulate Fixed 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| amount | float | 用于缩放 alpha 的百分比。 |

**返回：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 新图像效果在集合中的索引。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

在集合末尾添加新的 Alpha Replace 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**返回：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 新图像效果在集合中的索引。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

在集合末尾添加新的 Bi-Level (black/white) 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度阈值。大于等于阈值的值设为白色，小于阈值的值设为黑色。 |

**返回：**
[IBiLevel](../../com.aspose.slides/ibilevel) - 新图像效果在集合中的索引。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

在集合末尾添加新的 Blur 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 模糊半径。 |
| grow | boolean | 指定对象的边界是否因模糊而扩大。true 表示边界被扩大，false 表示不扩大。 |

**返回：**
[IBlur](../../com.aspose.slides/iblur) - 新图像效果在集合中的索引。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

在集合末尾添加新的 Color Change 效果。

**返回：**
[IColorChange](../../com.aspose.slides/icolorchange) - 新图像效果在集合中的索引。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

在集合末尾添加新的 Color Replacement 效果。

**返回：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 新图像效果在集合中的索引。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

在集合末尾添加新的 Duotone 效果。

**返回：**
[IDuotone](../../com.aspose.slides/iduotone) - 新图像效果在集合中的索引。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

在集合末尾添加新的 Fill Overlay 效果。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 新图像效果在集合中的索引。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

在集合末尾添加新的 Gray Scale 效果。

**返回：**
[IGrayScale](../../com.aspose.slides/igrayscale) - 新图像效果在集合中的索引。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

在集合末尾添加新的 Hue/Saturation/Luminance 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 调整色相的度数。 |
| saturation | float | 调整饱和度的百分比。 |
| luminance | float | 调整亮度的百分比。 |

**返回：**
[IHSL](../../com.aspose.slides/ihsl) - 新图像效果在集合中的索引。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

在集合末尾添加新的 Luminance 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 改变亮度的百分比。 |
| contrast | float | 改变对比度的百分比。 |

**返回：**
[ILuminance](../../com.aspose.slides/iluminance) - 新图像效果在集合中的索引。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

在集合末尾添加新的 Tint 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 要着色的色相。 |
| amount | float | 指定颜色值的偏移量。 |

**返回：**
[ITint](../../com.aspose.slides/itint) - 新图像效果在集合中的索引。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

在集合末尾添加新的 BrightnessContrast 效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 改变亮度的百分比。 |
| contrast | float | 改变对比度的百分比。 |

**返回：**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 新图像效果在集合中的索引。

### size() {#size--}
```
public final int size()
```

返回集合中图像效果的数量。只读 int。

**返回：**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否只读。只读 boolean。

**返回：**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 只读则为 true；否则为 false。

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

在集合末尾添加新的图像效果。

**参数：**
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 则为 true；否则为 false。

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | 接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素的一维数组。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的零基数组索引。 |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的对象。 |

**返回：**
boolean - 如果成功从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 则为 true；否则为 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，也返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

返回一个枚举器，用于遍历集合。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

为整个集合返回一个 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 整个集合的 java.util.Iterator。