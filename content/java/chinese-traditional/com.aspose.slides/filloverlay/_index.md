---
title: FillOverlay
second_title: Aspose.Slides for Java API 參考
description: 表示填充覆蓋效果。
type: docs
url: /zh-hant/com.aspose.slides/filloverlay/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**全部已實作的介面：**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

表示填充覆蓋效果。填充覆蓋可用於為物件指定額外的填充，並將兩個填充混合在一起。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 填充格式。 |
| [getBlend()](#getBlend--) | FillBlendMode。 |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效填充覆蓋效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 確定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等於目前的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

填充格式。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode。讀寫 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**返回：**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode。讀寫 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

取得套用繼承後的有效填充覆蓋效果資料。

**返回：**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - 一個 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。
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

確定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等於目前的 [FillOverlay](../../com.aspose.slides/filloverlay)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |
**返回：**
boolean - 若物件相等則返回 true；否則返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回：**
int - 目前物件的雜湊碼。