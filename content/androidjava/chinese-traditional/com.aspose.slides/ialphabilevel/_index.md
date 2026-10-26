---
title: IAlphaBiLevel
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Alpha 雙階層效果。
type: docs
url: /zh-hant/com.aspose.slides/ialphabilevel/
---
**所有已實作的介面:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

表示 Alpha 雙階層效果。小於閾值的 Alpha（不透明度）值將被更改為 0（完全透明），大於或等於閾值的 Alpha 值將被更改為 100%（完全不透明）。

--------------------

使用 ImageTransformOperationFactory 在 COM 中建立實例。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回效果閾值。 |
| [setThreshold(float value)](#setThreshold-float-) | 返回效果閾值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

返回效果閾值。讀寫 float。

**返回:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

返回效果閾值。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |