---
title: ColorReplace
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一種顏色取代效果。
type: docs
url: /zh-hant/com.aspose.slides/colorreplace/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面：**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

表示一種顏色取代效果。所有效果顏色皆會被更改為固定顏色。Alpha 值不受影響。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColor()](#getColor--) | 傳回將取代每個像素顏色的色彩格式。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效顏色取代效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [ColorReplace](../../com.aspose.slides/colorreplace) 是否等於目前的 [ColorReplace](../../com.aspose.slides/colorreplace)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


傳回將取代每個像素顏色的色彩格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


取得套用繼承後的有效顏色取代效果資料。

**傳回：**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - 一個 [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata)。
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long。

**傳回：**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


判斷指定的 [ColorReplace](../../com.aspose.slides/colorreplace) 是否等於目前的 [ColorReplace](../../com.aspose.slides/colorreplace)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [ColorReplace](../../com.aspose.slides/colorreplace)。 |

**傳回：**
boolean - 若物件相等則為 true；否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


作為特定類型的雜湊函式。

**傳回：**
int - 目前物件的雜湊碼。