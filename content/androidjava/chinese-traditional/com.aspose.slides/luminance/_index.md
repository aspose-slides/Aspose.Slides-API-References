---
title: Luminance
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個 Luminance 效果。
type: docs
url: /zh-hant/com.aspose.slides/luminance/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

代表一個 Luminance 效果。亮度線性地將所有顏色向白色或黑色靠近。對比度會將所有顏色的間距放大或縮小，使其更接近或更遠離。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Luminance 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Luminance](../../com.aspose.slides/luminance) 是否等於目前的 [Luminance](../../com.aspose.slides/luminance)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

取得套用繼承後的有效 Luminance 效果資料。

**傳回值:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - 一個 [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Luminance](../../com.aspose.slides/luminance) 是否等於目前的 [Luminance](../../com.aspose.slides/luminance)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [Luminance](../../com.aspose.slides/luminance)。 |

**傳回值:**
boolean - 如果物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回值:**
int - 目前物件的一個雜湊碼。