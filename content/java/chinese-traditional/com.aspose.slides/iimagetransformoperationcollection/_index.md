---
title: IImageTransformOperationCollection
second_title: Aspose.Slides Java API 參考
description: 表示套用於影像的效果集合。
type: docs
url: /zh-hant/com.aspose.slides/iimagetransformoperationcollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

表示套用於影像的效果集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 從集合中透過其索引返回一個 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)。 |
| [removeAt(int index)](#removeAt-int-) | 在指定的索引處從集合中移除影像效果。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 將新的 Alpha Bi-Level 效果新增至集合的末端。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 將新的 Alpha Ceiling 效果新增至集合的末端。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 將新的 Alpha Floor 效果新增至集合的末端。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 將新的 Alpha Inverse 效果新增至集合的末端。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 將新的 Alpha Modulate 效果新增至集合的末端。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 將新的 Alpha Modulate Fixed 效果新增至集合的末端。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 將新的 Alpha Replace 效果新增至集合的末端。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 將新的 Bi-Level（黑/白）效果新增至集合的末端。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 將新的 Blur 效果新增至集合的末端。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 將新的 Color Change 效果新增至集合的末端。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 將新的 Color Replacement 效果新增至集合的末端。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 將新的 Duotone 效果新增至集合的末端。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 將新的 Fill Overlay 效果新增至集合的末端。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 將新的 Gray Scale 效果新增至集合的末端。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 將新的 Hue/Saturation/Luminance 效果新增至集合的末端。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 將新的 Luminance 效果新增至集合的末端。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 將新的 Tint 效果新增至集合的末端。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 將新的 BrightnessContrast 效果新增至集合的末端。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

從集合中透過其索引返回一個 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 項目的索引。 |

**返回：**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 物件。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定的索引處從集合中移除影像效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要刪除的影像效果之索引。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

將新的 Alpha Bi-Level 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 效果的阈值。 |

**返回：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 新影像效果在集合中的索引。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

將新的 Alpha Ceiling 效果新增至集合的末端。

**返回：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 新影像效果在集合中的索引。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

將新的 Alpha Floor 效果新增至集合的末端。

**返回：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 新影像效果在集合中的索引。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

將新的 Alpha Inverse 效果新增至集合的末端。

**返回：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 新影像效果在集合中的索引。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

將新的 Alpha Modulate 效果新增至集合的末端。

**返回：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 新影像效果在集合中的索引。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

將新的 Alpha Modulate Fixed 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| amount | float | 用於縮放 alpha 的百分比。 |

**返回：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 新影像效果在集合中的索引。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

將新的 Alpha Replace 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

**返回：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 新影像效果在集合中的索引。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

將新的 Bi-Level（黑/白）效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度阈值。大於或等於阈值的值會被設定為白色。小於阈值的值會被設定為黑色。 |

**返回：**
[IBiLevel](../../com.aspose.slides/ibilevel) - 新影像效果在集合中的索引。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

將新的 Blur 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| radius | double | 模糊半徑。 |
| grow | boolean | 指定由於模糊而物件的邊界是否應該擴大。True 表示邊界會擴大，false 表示不會。 |

**返回：**
[IBlur](../../com.aspose.slides/iblur) - 新影像效果在集合中的索引。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

將新的 Color Change 效果新增至集合的末端。

**返回：**
[IColorChange](../../com.aspose.slides/icolorchange) - 新影像效果在集合中的索引。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

將新的 Color Replacement 效果新增至集合的末端。

**返回：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 新影像效果在集合中的索引。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

將新的 Duotone 效果新增至集合的末端。

**返回：**
[IDuotone](../../com.aspose.slides/iduotone) - 新影像效果在集合中的索引。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

將新的 Fill Overlay 效果新增至集合的末端。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 新影像效果在集合中的索引。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

將新的 Gray Scale 效果新增至集合的末端。

**返回：**
[IGrayScale](../../com.aspose.slides/igrayscale) - 新影像效果在集合中的索引。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

將新的 Hue/Saturation/Luminance 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hue | float | hue 調整的度數。 |
| saturation | float | saturation 調整的百分比。 |
| luminance | float | luminance 調整的百分比。 |

**返回：**
[IHSL](../../com.aspose.slides/ihsl) - 新影像效果在集合中的索引。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

將新的 Luminance 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brightness | float | 亮度變更的百分比。 |
| contrast | float | 對比度變更的百分比。 |

**返回：**
[ILuminance](../../com.aspose.slides/iluminance) - 新影像效果在集合中的索引。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

將新的 Tint 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hue | float | 要調整的 hue。 |
| amount | float | 指定顏色值的移動量。 |

**返回：**
[ITint](../../com.aspose.slides/itint) - 新影像效果在集合中的索引。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

將新的 BrightnessContrast 效果新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brightness | float | 亮度變更的百分比。 |
| contrast | float | 對比度變更的百分比。 |

**返回：**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 新影像效果在集合中的索引。