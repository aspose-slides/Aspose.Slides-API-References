---
title: AlphaModulateFixed
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 Alpha Modulate Fixed 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphamodulatefixed/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作介面:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

表示 Alpha Modulate Fixed 效果。效果的 alpha（不透明度）值會乘以一個固定的百分比。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getAmount()](#getAmount--) | 以百分比回傳效果量。 |
| [setAmount(float value)](#setAmount-float-) | 以百分比回傳效果量。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Modulate Fixed 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等於目前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getAmount() {#getAmount--}
```
public final float getAmount()
```

以百分比回傳效果量。可讀寫 float。

**返回值:**
float

### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

以百分比回傳效果量。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Modulate Fixed 效果資料。

**返回值:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - A [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等於目前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |

**返回值:**
boolean - 若物件相等則返回 true；否則返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回值:**
int - 目前物件的雜湊碼。