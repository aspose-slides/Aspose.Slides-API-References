---
title: HSL
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表 Hue/Saturation/Luminance 效果。
type: docs
url: /zh-hant/com.aspose.slides/hsl/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

代表 Hue/Saturation/Luminance 效果。色相、飽和度與亮度皆可相對於目前值進行調整。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Hue/Saturation/Luminance 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [HSL](../../com.aspose.slides/hsl) 是否等於目前的 [HSL](../../com.aspose.slides/hsl)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


取得套用繼承後的有效 Hue/Saturation/Luminance 效果資料。

**回傳值：**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - 一個 [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


判斷指定的 [HSL](../../com.aspose.slides/hsl) 是否等於目前的 [HSL](../../com.aspose.slides/hsl)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [HSL](../../com.aspose.slides/hsl)。 |

**回傳值：**
boolean - true 如果物件相等；否則，false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


作為特定類型的雜湊函式。

**回傳值：**
int - 目前物件的雜湊碼。