---
title: AlphaBiLevel
second_title: Aspose.Slides for Java API 參考文件
description: 表示 Alpha 雙層效果。
type: docs
url: /zh-hant/com.aspose.slides/alphabilevel/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

表示 Alpha Bi-Level 效果。小於閾值的 Alpha（Opacity）值會變為 0（完全透明），而大於或等於閾值的 Alpha 值會變為 100%（完全不透明）。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 傳回效果閾值。 |
| [setThreshold(float value)](#setThreshold-float-) | 傳回效果閾值。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Bi-Level 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel) 是否等於目前的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


傳回效果閾值。可讀寫 float.

**傳回值:**
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


傳回效果閾值。可讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


取得套用繼承後的有效 Alpha Bi-Level 效果資料。

**傳回值:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - 一個 [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


判斷指定的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel) 是否等於目前的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |

**傳回值:**
boolean - 若物件相等則返回 true；否則返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


作為特定類型的雜湊函式。

**傳回值:**
int - 目前物件的雜湊碼。