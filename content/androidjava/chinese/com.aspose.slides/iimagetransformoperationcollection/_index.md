---
title: IImageTransformOperationCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示一个应用于图像的效果集合。
type: docs
url: /zh/com.aspose.slides/iimagetransformoperationcollection/
---
**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

表示一个应用于图像的效果集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 通过其索引从集合中返回一个 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 在指定的索引处从集合中删除图像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 将新的 Alpha Bi-Level 效果添加到集合的末尾。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 将新的 Alpha Ceiling 效果添加到集合的末尾。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 将新的 Alpha Floor 效果添加到集合的末尾。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 将新的 Alpha Inverse 效果添加到集合的末尾。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 将新的 Alpha Modulate 效果添加到集合的末尾。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 将新的 Alpha Modulate Fixed 效果添加到集合的末尾。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 将新的 Alpha Replace 效果添加到集合的末尾。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 将新的 Bi-Level（黑/白）效果添加到集合的末尾。 |
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

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

通过其索引从集合中返回一个 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 项的索引。 |

**返回:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 对象。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定的索引处从集合中删除图像效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应被删除的图像效果的索引。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

将新的 Alpha Bi-Level 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的阈值。 |

**返回:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 集合中新图像效果的索引。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

将新的 Alpha Ceiling 效果添加到集合的末尾。

**返回:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 集合中新图像效果的索引。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

将新的 Alpha Floor 效果添加到集合的末尾。

**返回:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 集合中新图像效果的索引。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

将新的 Alpha Inverse 效果添加到集合的末尾。

**返回:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 集合中新图像效果的索引。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

将新的 Alpha Modulate 效果添加到集合的末尾。

**返回:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 集合中新图像效果的索引。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

将新的 Alpha Modulate Fixed 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| amount | float | Alpha 的百分比缩放量。 |

**返回:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 集合中新图像效果的索引。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

将新的 Alpha Replace 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**返回:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 集合中新图像效果的索引。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

将新的 Bi-Level（黑/白）效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度阈值。大于等于阈值的值设为白色，小于阈值的值设为黑色。 |

**返回:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 集合中新图像效果的索引。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

将新的 Blur 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 模糊半径。 |
| grow | boolean | 指定模糊后对象的边界是否应扩展。True 表示边界会扩展，false 表示不扩展。 |

**返回:**
[IBlur](../../com.aspose.slides/iblur) - 集合中新图像效果的索引。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

将新的 Color Change 效果添加到集合的末尾。

**返回:**
[IColorChange](../../com.aspose.slides/icolorchange) - 集合中新图像效果的索引。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

将新的 Color Replacement 效果添加到集合的末尾。

**返回:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 集合中新图像效果的索引。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

将新的 Duotone 效果添加到集合的末尾。

**返回:**
[IDuotone](../../com.aspose.slides/iduotone) - 集合中新图像效果的索引。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

将新的 Fill Overlay 效果添加到集合的末尾。

**返回:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 集合中新图像效果的索引。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

将新的 Gray Scale 效果添加到集合的末尾。

**返回:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 集合中新图像效果的索引。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

将新的 Hue/Saturation/Luminance 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 色相调整的度数。 |
| saturation | float | 饱和度调整的百分比。 |
| luminance | float | 亮度调整的百分比。 |

**返回:**
[IHSL](../../com.aspose.slides/ihsl) - 集合中新图像效果的索引。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

将新的 Luminance 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 亮度的百分比变化。 |
| contrast | float | 对比度的百分比变化。 |

**返回:**
[ILuminance](../../com.aspose.slides/iluminance) - 集合中新图像效果的索引。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

将新的 Tint 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 要染色的目标色相。 |
| amount | float | 指定颜色值的偏移量。 |

**返回:**
[ITint](../../com.aspose.slides/itint) - 集合中新图像效果的索引。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

将新的 BrightnessContrast 效果添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 亮度的百分比变化。 |
| contrast | float | 对比度的百分比变化。 |

**返回:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 集合中新图像效果的索引。