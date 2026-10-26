---
title: HSL
second_title: Aspose.Slides for Java API 參考文件
description: 表示一種色相/飽和度/亮度效果。
type: docs
url: /zh-hant/com.aspose.slides/hsl/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**已實作的介面：**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

表示一種色相/飽和度/亮度效果。色相、飽和度與亮度皆可相對於目前的值進行調整。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效色相/飽和度/亮度效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [HSL](../../com.aspose.slides/hsl) 是否等於目前的 [HSL](../../com.aspose.slides/hsl)。 |
| [hashCode()](#hashCode--) | 為特定類型提供雜湊函式。 |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

取得套用繼承後的有效色相/飽和度/亮度效果資料。

**傳回值：**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - 一個 [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [HSL](../../com.aspose.slides/hsl) 是否等於目前的 [HSL](../../com.aspose.slides/hsl)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [HSL](../../com.aspose.slides/hsl)。 |

**傳回值：**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

為特定類型提供雜湊函式。

**傳回值：**
int - 一個針對目前物件的雜湊碼。