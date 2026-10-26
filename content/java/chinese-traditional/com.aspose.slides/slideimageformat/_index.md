---
title: SlideImageFormat
second_title: Aspose.Slides Java API 參考文件
description: 決定投影片圖像在 HTML 匯出時的儲存格式。
type: docs
url: /zh-hant/com.aspose.slides/slideimageformat/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

決定投影片圖像在 HTML 匯出時的儲存格式。

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | 投影片應以 SVG 格式轉換。 |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | 投影片應以點陣圖格式轉換。 |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


投影片應以 SVG 格式轉換。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG 匯出的選項。 |

**回傳值:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) 物件。

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


投影片應以點陣圖格式轉換。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| scale | float | 輸出圖像的縮放比例。 |
| imageFormat | int | 產生影像的格式（例如 PNG、JPEG）。 |

**回傳值:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - 