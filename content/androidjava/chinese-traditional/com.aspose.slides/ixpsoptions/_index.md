---
title: IXpsOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 提供控制簡報以 XPS 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/ixpsoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in XPS format.
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True 轉換簡報中使用的所有圖形檔為 PNG 圖像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True 轉換簡報中使用的所有圖形檔為 PNG 圖像。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True 在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True 在每張投影片周圍繪製黑色框線。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏的投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏的投影片。 |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True 轉換簡報中使用的所有圖形檔為 PNG 圖像。 可讀寫布林值。

--------------------

預設為 **true**。

**返回:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True 轉換簡報中使用的所有圖形檔為 PNG 圖像。 可讀寫布林值。

--------------------

預設為 **true**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True 在每張投影片周圍繪製黑色框線。 可讀寫布林值。

--------------------

預設為 **false**。

**返回:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True 在每張投影片周圍繪製黑色框線。 可讀寫布林值。

--------------------

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏的投影片。 預設為 false。

**返回:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏的投影片。 預設為 false。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |