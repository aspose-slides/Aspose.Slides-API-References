---
title: Duotone
second_title: Aspose.Slides for Java API 參考
description: 表示雙音調效果。
type: docs
url: /zh-hant/com.aspose.slides/duotone/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有實作的介面:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

表示雙音調效果。對於每個像素，通過線性插值結合 Color1 和 Color2 以確定該像素的新顏色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目標顏色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目標顏色格式。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效雙音調效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Duotone](../../com.aspose.slides/duotone) 是否等於當前的 [Duotone](../../com.aspose.slides/duotone)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

返回暗像素的目標顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

返回亮像素的目標顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

取得套用繼承後的有效雙音調效果資料。

**返回值:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回值:**  
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Duotone](../../com.aspose.slides/duotone) 是否等於當前的 [Duotone](../../com.aspose.slides/duotone)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [Duotone](../../com.aspose.slides/duotone)。 |

**返回值:**  
boolean - 若物件相等則為 true；否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回值:**  
int - 當前物件的雜湊碼。