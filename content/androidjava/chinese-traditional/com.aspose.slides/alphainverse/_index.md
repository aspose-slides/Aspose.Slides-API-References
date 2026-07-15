---
title: AlphaInverse
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 Alpha Inverse 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphainverse/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

表示 Alpha Inverse 效果。Alpha（不透明度）值透過從 100% 減去來反轉。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Inverse 效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaInverse](../../com.aspose.slides/alphainverse) 是否等於目前的 [AlphaInverse](../../com.aspose.slides/alphainverse)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Inverse 效果資料。

**返回:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - 一個 [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaInverse](../../com.aspose.slides/alphainverse) 是否等於目前的 [AlphaInverse](../../com.aspose.slides/alphainverse)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [AlphaInverse](../../com.aspose.slides/alphainverse)。 |

**返回:**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回:**
int - 目前物件的雜湊碼。