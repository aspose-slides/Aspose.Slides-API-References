---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /zh-hant/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

代表 SvgImageSavingDelegate.SvgImageSavingDelegate 事件的 markdown SVG 圖像儲存處理程序。

## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | 在 Markdown 匯出期間對每個 SVG 圖像呼叫。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

在 Markdown 匯出期間對每個 SVG 圖像呼叫。傳回 true 以使用指定的 link，或傳回 false 以套用預設的儲存邏輯。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 正在匯出的 SVG 圖像。 |
| link | java.lang.String[] | 當傳回 true 時使用的 Markdown link。 |

**返回值：**
boolean