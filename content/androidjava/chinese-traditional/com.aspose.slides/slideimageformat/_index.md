---
title: SlideImageFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 確定在匯出為 HTML 時，投影片影像的儲存格式。
type: docs
url: /zh-hant/com.aspose.slides/slideimageformat/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```

確定投影片影像在匯出為 HTML 時的儲存格式。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG 匯出的選項。 |

**回傳值:**  
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) 物件。

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

投影片應轉換為點陣圖影像。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scale | float | 縮放輸出影像的比例因子。 |
| imageFormat | int | 產生影像的格式（例如 PNG、JPEG）。 |

**回傳值:**  
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -