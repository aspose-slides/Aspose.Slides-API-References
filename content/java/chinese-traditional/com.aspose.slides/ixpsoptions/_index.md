---
title: IXpsOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制簡報以 XPS 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/ixpsoptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

提供控制簡報以 XPS 格式保存方式的選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 設定為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 設定為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 設定為 true 以在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 設定為 true 以在每張投影片周圍繪製黑色框線。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應該包含隱藏的投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應該包含隱藏的投影片。 |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

設定為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。讀/寫布林值。

--------------------

預設為 **true**。

**返回值：**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

設定為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。讀/寫布林值。

--------------------

預設為 **true**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

設定為 true 以在每張投影片周圍繪製黑色框線。讀/寫布林值。

--------------------

預設為 **false**。

**返回值：**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

設定為 true 以在每張投影片周圍繪製黑色框線。讀/寫布林值。

--------------------

預設為 **false**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定產生的文件是否應該包含隱藏的投影片。預設為 false。

**返回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應該包含隱藏的投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |