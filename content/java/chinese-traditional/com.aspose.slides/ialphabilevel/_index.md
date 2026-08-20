---
title: IAlphaBiLevel
second_title: Aspose.Slides for Java API 參考
description: 代表 Alpha Bi-Level 效果。
type: docs
url: /zh-hant/com.aspose.slides/ialphabilevel/
---
**所有已實作的介面:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

代表 Alpha Bi-Level 效果。Alpha (Opacity) 小於閾值的值會被更改為 0（完全透明），而大於或等於閾值的 alpha 值會被更改為 100%（完全不透明）。

--------------------

使用 ImageTransformOperationFactory 在 COM 中建立實例。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 傳回效果閾值。 |
| [setThreshold(float value)](#setThreshold-float-) | 傳回效果閾值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

傳回效果閾值。可讀寫 float。

**傳回:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

傳回效果閾值。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |