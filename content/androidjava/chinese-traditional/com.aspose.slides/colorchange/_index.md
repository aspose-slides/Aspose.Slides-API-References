---
title: ColorChange
second_title: Aspose.Slides for Android via Java API 參考
description: 表示顏色變更效果。
type: docs
url: /zh-hant/com.aspose.slides/colorchange/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**  
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect  
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

表示顏色變更效果。FromColor 的實例會被 ToColor 的實例所取代。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 將被取代的顏色。 |
| [getToColor()](#getToColor--) | 將取代的顏色。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效顏色變更效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [ColorChange](../../com.aspose.slides/colorchange) 是否等於目前的 [ColorChange](../../com.aspose.slides/colorchange)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

將被取代的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

將取代的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

取得套用繼承後的有效顏色變更效果資料。

**返回：**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - 一個 [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [ColorChange](../../com.aspose.slides/colorchange) 是否等於目前的 [ColorChange](../../com.aspose.slides/colorchange)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [ColorChange](../../com.aspose.slides/colorchange)。 |

**返回：**  
boolean - 若物件相等則回傳 true；否則回傳 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回：**  
int - 目前物件的雜湊碼。