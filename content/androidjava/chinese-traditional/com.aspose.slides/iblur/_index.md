---
title: IBlur
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示套用於整個形狀（包括填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/iblur/
---
**所有已實作的介面:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

表示套用於整個形狀（包括其填充）的模糊效果。所有顏色通道，包括 Alpha，都會受到影響。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或設定模糊半徑。 |
| [setRadius(double value)](#setRadius-double-) | 返回或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 判斷因模糊而導致的物件邊界是否應該擴大。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 判斷因模糊而導致的物件邊界是否應該擴大。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


返回或設定模糊半徑。 讀寫 double.

**返回:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


返回或設定模糊半徑。 讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


判斷因模糊而導致的物件邊界是否應該擴大。 true 表示邊界會擴大，false 表示不會。 讀寫 boolean.

**返回:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


判斷因模糊而導致的物件邊界是否應該擴大。 true 表示邊界會擴大，false 表示不會。 讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |