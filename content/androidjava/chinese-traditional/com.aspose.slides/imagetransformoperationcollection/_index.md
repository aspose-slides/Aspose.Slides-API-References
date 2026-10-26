---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示套用於影像的效果集合。
type: docs
url: /zh-hant/com.aspose.slides/imagetransformoperationcollection/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

表示套用於影像的效果集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | 從集合中依索引返回一個 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中於指定的索引移除影像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 將新的 Alpha Bi-Level 效果加入集合的末端。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 將新的 Alpha Ceiling 效果加入集合的末端。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 將新的 Alpha Floor 效果加入集合的末端。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 將新的 Alpha Inverse 效果加入集合的末端。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 將新的 Alpha Modulate 效果加入集合的末端。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 將新的 Alpha Modulate Fixed 效果加入集合的末端。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 將新的 Alpha Replace 效果加入集合的末端。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 將新的 Bi-Level (black/white) 效果加入集合的末端。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 將新的 Blur 效果加入集合的末端。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 將新的 Color Change 效果加入集合的末端。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 將新的 Color Replacement 效果加入集合的末端。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 將新的 Duotone 效果加入集合的末端。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 將新的 Fill Overlay 效果加入集合的末端。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 將新的 Gray Scale 效果加入集合的末端。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 將新的 Hue/Saturation/Luminance 效果加入集合的末端。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 將新的 Luminance 效果加入集合的末端。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 將新的 Tint 效果加入集合的末端。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 將新的 BrightnessContrast 效果加入集合的末端。 |
| [size()](#size--) | 返回集合中影像效果的數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 將新的影像效果加入集合的末端。 |
| [clear()](#clear--) | 從集合中移除所有影像效果。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | 將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製至陣列，從特定的陣列索引開始。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除首次出現的特定物件。 |
| [iterator()](#iterator--) | 返回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 Java 迭代器。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**Returns:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

從集合中依索引返回一個 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 物件。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中於指定的索引移除影像效果。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int | 應該要刪除的影像效果之索引。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

將新的 Alpha Bi-Level 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的臨界值。 |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 新影像效果在集合中的索引。
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

將新的 Alpha Ceiling 效果加入集合的末端。

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 新影像效果在集合中的索引。
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

將新的 Alpha Floor 效果加入集合的末端。

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 新影像效果在集合中的索引。
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

將新的 Alpha Inverse 效果加入集合的末端。

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 新影像效果在集合中的索引。
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

將新的 Alpha Modulate 效果加入集合的末端。

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 新影像效果在集合中的索引。
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

將新的 Alpha Modulate Fixed 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| amount | float | 用於縮放 Alpha 的百分比。 |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 新影像效果在集合中的索引。
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

將新的 Alpha Replace 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 新影像效果在集合中的索引。
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

將新的 Bi-Level (black/white) 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度臨界值。大於或等於臨界值的會設為白色，小於臨界值的會設為黑色。 |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 新影像效果在集合中的索引。
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

將新的 Blur 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| radius | double | 模糊的半徑。 |
| grow | boolean | 指定因模糊而導致物件邊界是否增大。true 表示邊界會增大，false 表示不增大。 |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - 新影像效果在集合中的索引。
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

將新的 Color Change 效果加入集合的末端。

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - 新影像效果在集合中的索引。
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

將新的 Color Replacement 效果加入集合的末端。

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 新影像效果在集合中的索引。
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

將新的 Duotone 效果加入集合的末端。

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - 新影像效果在集合中的索引。
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

將新的 Fill Overlay 效果加入集合的末端。

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 新影像效果在集合中的索引。
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

將新的 Gray Scale 效果加入集合的末端。

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 新影像效果在集合中的索引。
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

將新的 Hue/Saturation/Luminance 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| hue | float | 色相調整的度數。 |
| saturation | float | 飽和度調整的百分比。 |
| luminance | float | 亮度調整的百分比。 |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - 新影像效果在集合中的索引。
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

將新的 Luminance 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| brightness | float | 變更亮度的百分比。 |
| contrast | float | 變更對比的百分比。 |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - 新影像效果在集合中的索引。
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

將新的 Tint 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| hue | float | 要著色的色相。 |
| amount | float | 指定顏色值的偏移量。 |

**Returns:**
[ITint](../../com.aspose.slides/itint) - 新影像效果在集合中的索引。
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

將新的 BrightnessContrast 效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| brightness | float | 變更亮度的百分比。 |
| contrast | float | 變更對比的百分比。 |

**Returns:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 新影像效果在集合中的索引。
### size() {#size--}
```
public final int size()
```

返回集合中影像效果的數量。唯讀 int 。

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。唯讀 boolean。

**Returns:**
boolean - 若 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則返回 true；否則返回 false。
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

將新的影像效果加入集合的末端。

**Parameters:**
| 參數 | 型別 | 描述 |
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

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**Returns:**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則返回 true；否則返回 false。
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製至陣列，從特定的陣列索引開始。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | 接收從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製之元素的一維陣列。該陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始的零基陣列索引。 |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除首次出現的特定物件。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**Returns:**
boolean - 若成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 則返回 true；否則返回 false。若在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找不到 item，亦返回 false。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

返回遍歷集合的列舉器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

返回整個集合的 Java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 用於整個集合的 java.util.Iterator。