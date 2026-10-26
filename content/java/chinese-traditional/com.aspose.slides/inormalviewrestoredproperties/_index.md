---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Java API Reference
description: Specifies the sizing of the slide region width when a child of restoredTop height when a child of restoredLeft of the normal view when the region is of a variable restored sizeneither minimized nor maximized.
type: docs
url: /zh-hant/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

指定投影片區域的尺寸（當子項位於 restoredTop 時為寬度，當子項位於 restoredLeft 時為高度），此為標準檢視中的正常大小，且區域處於可變的還原尺寸（既未最小化亦未最大化）。
## 方法

| Method | Description |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 指定投影片區域的大小（當子項位於 RestoredTop 時為寬度，當子項位於 RestoredLeft 時為高度）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 指定投影片區域的大小（當子項位於 RestoredTop 時為寬度，當子項位於 RestoredLeft 時為高度）。 |
| [getAutoAdjust()](#getAutoAdjust--) | 指定在調整包含此檢視之視窗大小時，側邊內容區域的大小是否應補償新的大小。Read/write boolean。 |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 指定在調整包含此檢視之視窗大小時，側邊內容區域的大小是否應補償新的大小。Read/write boolean。 |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

指定投影片區域的大小（當子項位於 RestoredTop 時為寬度，當子項位於 RestoredLeft 時為高度）。Read/write float.

**傳回：**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

指定投影片區域的大小（當子項位於 RestoredTop 時為寬度，當子項位於 RestoredLeft 時為高度）。Read/write float。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

指定在調整包含此檢視之視窗大小時，側邊內容區域的大小是否應補償新的大小。Read/write boolean。

**傳回：**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

指定在調整包含此檢視之視窗大小時，側邊內容區域的大小是否應補償新的大小。Read/write boolean。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |