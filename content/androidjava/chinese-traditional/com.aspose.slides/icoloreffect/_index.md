---
title: IColorEffect
second_title: Aspose.Slides for Android via Java API 參考
description: 表示動畫行為的顏色效果。
type: docs
url: /zh-hant/com.aspose.slides/icoloreffect/
---
**所有已實作的介面：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

表示動畫行為的顏色效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 此值用於指定行為的起始顏色。 |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | 此值用於指定行為的起始顏色。 |
| [getTo()](#getTo--) | 描述動畫顏色變化的結果顏色。 |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | 描述動畫顏色變化的結果顏色。 |
| [getBy()](#getBy--) | 描述顏色動畫的相對偏移值。 |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | 描述顏色動畫的相對偏移值。 |
| [getColorSpace()](#getColorSpace--) | 表示行為的色彩空間。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 表示行為的色彩空間。 |
| [getDirection()](#getDirection--) | 指定在色相環上循環色相的方向。 |
| [setDirection(int value)](#setDirection-int-) | 指定在色相環上循環色相的方向。 |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

此值用於指定行為的起始顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**回傳：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

此值用於指定行為的起始顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

描述動畫顏色變化的結果顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**回傳：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

描述動畫顏色變化的結果顏色。讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

描述顏色動畫的相對偏移值。讀寫 [IColorOffset](../../com.aspose.slides/icoloroffset)。

**回傳：**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

描述顏色動畫的相對偏移值。讀寫 [IColorOffset](../../com.aspose.slides/icoloroffset)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

表示行為的色彩空間。讀寫 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**回傳：**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

表示行為的色彩空間。讀寫 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

指定在色相環上循環色相的方向。讀寫 [ColorDirection](../../com.aspose.slides/colordirection)。

**回傳：**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

指定在色相環上循環色相的方向。讀寫 [ColorDirection](../../com.aspose.slides/colordirection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |