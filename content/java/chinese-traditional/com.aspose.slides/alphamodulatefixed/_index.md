---
title: AlphaModulateFixed
second_title: Aspose.Slides for Java API 參考
description: 表示 Alpha Modulate Fixed 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphamodulatefixed/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

表示 Alpha Modulate Fixed 效果。效果 alpha（不透明度）值會乘以固定的百分比。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAmount()](#getAmount--) | 返回效果的百分比。 |
| [setAmount(float value)](#setAmount-float-) | 返回效果的百分比。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Modulate Fixed 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等於目前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getAmount() {#getAmount--}
```
public final float getAmount()
```


返回效果的百分比。讀/寫 float。

**返回:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```


返回效果的百分比。讀/寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```


取得套用繼承後的有效 Alpha Modulate Fixed 效果資料。

**返回:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - 一個 [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


判斷指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等於目前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) |

**返回:**
boolean - 若物件相等則為 true；否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


作為特定類型的雜湊函式。

**返回:**
int - 目前物件的雜湊碼。