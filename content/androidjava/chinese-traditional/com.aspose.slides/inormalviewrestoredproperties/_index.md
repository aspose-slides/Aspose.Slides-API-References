---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the sizing of the slide region width when a child of restoredTop height when a child of restoredLeft of the normal view when the region is of a variable restored sizeneither minimized nor maximized.
type: docs
url: /zh-hant/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

指定普通檢視中幻燈片區域的尺寸（子項為 RestoredTop 時的寬度，子項為 RestoredLeft 時的高度），當區域處於可變的還原大小（既非最小化也非最大化）時。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 指定幻燈片區域的尺寸（子項為 RestoredTop 時的寬度，子項為 RestoredLeft 時的高度）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 指定幻燈片區域的尺寸（子項為 RestoredTop 時的寬度，子項為 RestoredLeft 時的高度）。 |
| [getAutoAdjust()](#getAutoAdjust--) | 指定在調整包含視圖的視窗大小時，側內容區域的尺寸是否應補償新的大小。可讀寫 boolean。 |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 指定在調整包含視圖的視窗大小時，側內容區域的尺寸是否應補償新的大小。可讀寫 boolean。 |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

指定幻燈片區域的尺寸（子項為 RestoredTop 時的寬度，子項為 RestoredLeft 時的高度）。可讀寫 float。

**返回值:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

指定幻燈片區域的尺寸（子項為 RestoredTop 時的寬度，子項為 RestoredLeft 時的高度）。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

指定在調整包含視圖的視窗大小時，側內容區域的尺寸是否應補償新的大小。可讀寫 boolean。

**返回值:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

指定在調整包含視圖的視窗大小時，側內容區域的尺寸是否應補償新的大小。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |