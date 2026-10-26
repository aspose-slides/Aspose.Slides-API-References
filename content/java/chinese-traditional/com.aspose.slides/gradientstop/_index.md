---
title: GradientStop
second_title: Aspose.Slides for Java API 參考
description: 表示漸層格式。
type: docs
url: /zh-hant/com.aspose.slides/gradientstop/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**  
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)  
```
public final class GradientStop extends PVIObject implements IGradientStop
```

表示漸層格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 回傳或設定漸層停止點的位置 (0..1)。 |
| [setPosition(float value)](#setPosition-float-) | 回傳或設定漸層停止點的位置 (0..1)。 |
| [getColor()](#getColor--) | 回傳漸層停止點的顏色。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只讀 long。

**傳回:**  
long

### getPosition() {#getPosition--}
```
public final float getPosition()
```

回傳或設定漸層停止點的位置 (0..1)。讀寫  float 。

**傳回:**  
float

### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

回傳或設定漸層停止點的位置 (0..1)。讀寫  float 。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

回傳漸層停止點的顏色。只讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回:**  
[IColorFormat](../../com.aspose.slides/icolorformat)