---
title: FillOverlay
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Fill Overlay 效果。
type: docs
url: /zh-hant/com.aspose.slides/filloverlay/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

表示 Fill Overlay 效果。Fill Overlay 可用於為物件指定額外的填充，並將兩個填充混合在一起。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 填充格式。 |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Fill Overlay 效果資料。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 確定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等於目前的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

填充格式。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**回傳：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. 可讀寫 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**回傳：**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. 可讀寫 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

取得套用繼承後的有效 Fill Overlay 效果資料。

**回傳：**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - 一個 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**回傳：**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

確定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等於目前的 [FillOverlay](../../com.aspose.slides/filloverlay)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |

**回傳：**
boolean - 若物件相等則傳回 true；否則傳回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**回傳：**
int - 目前物件的雜湊碼。