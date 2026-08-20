---
title: ImageTransformOperationCollection
second_title: Aspose.Slides 的 Java API 參考
description: 表示套用於影像的效果集合。
type: docs
url: /zh-hant/com.aspose.slides/imagetransformoperationcollection/
---
**繼承關係：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已實作介面：**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

表示套用於影像的效果集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | 從集合中依索引傳回一個 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 在指定的索引處從集合中移除影像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 將新的 Alpha Bi-Level 效果加入集合的末端。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 將新的 Alpha Ceiling 效果加入集合的末端。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 將新的 Alpha Floor 效果加入集合的末端。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 將新的 Alpha Inverse 效果加入集合的末端。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 將新的 Alpha Modulate 效果加入集合的末端。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 將新的 Alpha Modulate Fixed 效果加入集合的末端。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 将新的 Alpha Replace 效果加入集合的末端。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 将新的 Bi-Level（黑/白）效果加入集合的末端。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 将新的 Blur 效果加入集合的末端。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 将新的 Color Change 效果加入集合的末端。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 将新的 Color Replacement 效果加入集合的末端。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 将新的 Duotone 效果加入集合的末端。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 将新的 Fill Overlay 效果加入集合的末端。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 将新的 Gray Scale 效果加入集合的末端。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 将新的 Hue/Saturation/Luminance 效果加入集合的末端。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 将新的 Luminance 效果加入集合的末端。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 将新的 Tint 效果加入集合的末端。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 将新的 BrightnessContrast 效果加入集合的末端。 |
| [size()](#size--) | 传回集合中影像效果的数量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为唯读的值。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 将新的影像效果加入集合的末端。 |
| [clear()](#clear--) | 从集合中移除所有影像效果。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | 判断 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到阵列，從特定的阵列索引开始。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除首次出现的特定对象。 |
| [iterator()](#iterator--) | 传回一个可遍历集合的列举器。 |
| [iteratorJava()](#iteratorJava--) | 传回整个集合的 java 迭代器。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯读 long。

**傳回：**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

從集合中依索引傳回一個 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回：**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 物件。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定的索引處從集合中移除影像效果。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要刪除的影像效果的索引。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

將新的 Alpha Bi-Level 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的閾值。 |

**傳回：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 新影像效果在集合中的索引。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

將新的 Alpha Ceiling 效果加入集合的末端。

**傳回：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 新影像效果在集合中的索引。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

將新的 Alpha Floor 效果加入集合的末端。

**傳回：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 新影像效果在集合中的索引。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

將新的 Alpha Inverse 效果加入集合的末端。

**傳回：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 新影像效果在集合中的索引。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

將新的 Alpha Modulate 效果加入集合的末端。

**傳回：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 新影像效果在集合中的索引。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

將新的 Alpha Modulate Fixed 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Alpha 的縮放百分比。 |

**傳回：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 新影像效果在集合中的索引。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

將新的 Alpha Replace 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**傳回：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 新影像效果在集合中的索引。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

將新的 Bi-Level（黑/白）效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度閾值。大於或等於閾值的設為白色，小於閾值的設為黑色。 |

**傳回：**
[IBiLevel](../../com.aspose.slides/ibilevel) - 新影像效果在集合中的索引。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

將新的 Blur 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | 模糊半徑。 |
| grow | boolean | 指示是否因模糊而擴大物件的邊界。true 表示邊界會擴大，false 表示不會。 |

**傳回：**
[IBlur](../../com.aspose.slides/iblur) - 新影像效果在集合中的索引。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

將新的 Color Change 效果加入集合的末端。

**傳回：**
[IColorChange](../../com.aspose.slides/icolorchange) - 新影像效果在集合中的索引。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

將新的 Color Replacement 效果加入集合的末端。

**傳回：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 新影像效果在集合中的索引。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

將新的 Duotone 效果加入集合的末端。

**傳回：**
[IDuotone](../../com.aspose.slides/iduotone) - 新影像效果在集合中的索引。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

將新的 Fill Overlay 效果加入集合的末端。

**傳回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 新影像效果在集合中的索引。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

將新的 Gray Scale 效果加入集合的末端。

**傳回：**
[IGrayScale](../../com.aspose.slides/igrayscale) - 新影像效果在集合中的索引。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

將新的 Hue/Saturation/Luminance 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 色相的調整角度（度）。 |
| saturation | float | 飽和度的調整百分比。 |
| luminance | float | 亮度的調整百分比。 |

**傳回：**
[IHSL](../../com.aspose.slides/ihsl) - 新影像效果在集合中的索引。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

將新的 Luminance 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | 亮度的變更百分比。 |
| contrast | float | 對比度的變更百分比。 |

**傳回：**
[ILuminance](../../com.aspose.slides/iluminance) - 新影像效果在集合中的索引。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

將新的 Tint 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 要調整的色相。 |
| amount | float | 指定顏色值的偏移量。 |

**傳回：**
[ITint](../../com.aspose.slides/itint) - 新影像效果在集合中的索引。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

將新的 BrightnessContrast 效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | 亮度的變更百分比。 |
| contrast | float | 對比度的變更百分比。 |

**傳回：**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 新影像效果在集合中的索引。

### size() {#size--}
```
public final int size()
```

傳回集合中影像效果的数量。唯读 int 。

**傳回：**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为唯读的值。唯读 boolean 。

**傳回：**
boolean - 若 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为唯读则返回 true；否则返回 false。

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

將新的影像效果加入集合的末端。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要加入集合末端的影像效果。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有影像效果。

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**傳回：**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 則返回 true；否则返回 false。

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到阵列，從特定的阵列索引開始。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製的元素之目的一維陣列。陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始的零基索引。 |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一次出現的特定物件。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**傳回：**
boolean - 若成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 則返回 true；否则返回 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，亦返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

傳回一個可遍歷集合的列舉器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 整個集合的 java.util.Iterator。