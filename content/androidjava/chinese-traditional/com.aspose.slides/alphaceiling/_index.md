---
title: AlphaCeiling
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示 Alpha Ceiling 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphaceiling/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作介面:**  
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect  
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

表示 Alpha Ceiling 效果。Alpha（不透明度）值大於零的將被更改為 100%。換句話說，任何部分透明的物件將變為完全不透明。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Ceiling 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaCeiling](../../com.aspose.slides/alphaceiling) 是否等於目前的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Ceiling 效果資料。

**回傳值:**  
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - 一個 [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaCeiling](../../com.aspose.slides/alphaceiling) 是否等於目前的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。 |

**回傳值:**  
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**回傳值:**  
int - 目前物件的雜湊碼。