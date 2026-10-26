---
title: IBlur
second_title: Aspose.Slides for Java API 參考
description: 表示套用於整個形狀（包括其填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/iblur/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

表示套用於整個形狀（包括其填充）的模糊效果。所有顏色通道，包括 alpha，皆會受到影響。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 傳回或設定模糊半徑。 |
| [setRadius(double value)](#setRadius-double-) | 傳回或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 判斷在模糊處理後是否應擴大物件的邊界。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 判斷在模糊處理後是否應擴大物件的邊界。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


傳回或設定模糊半徑。讀/寫 double。

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


傳回或設定模糊半徑。讀/寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


判斷在模糊處理後物件的邊界是否應擴大。True 表示邊界會被擴大，false 表示不會。讀/寫 boolean。

**返回：**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


判斷在模糊處理後物件的邊界是否應擴大。True 表示邊界會被擴大，false 表示不會。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |