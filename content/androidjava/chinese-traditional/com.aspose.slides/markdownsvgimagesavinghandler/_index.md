---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 SvgImageSavingDelegate.SvgImageSavingDelegate 事件的 markdown SVG 圖像保存處理程序。
type: docs
url: /zh-hant/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

表示 markdown SVG 圖像保存處理程序的 \#SvgImageSavingDelegate.SvgImageSavingDelegate 事件。
## Methods

| 方法 | 說明 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | 在 Markdown 匯出期間對每個 SVG 圖像呼叫。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

在 Markdown 匯出期間對每個 SVG 圖像呼叫。傳回 true 以使用指定的連結，或傳回 false 以套用預設的儲存邏輯。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 正在匯出的 SVG 圖像。 |
| link | java.lang.String[] | 傳回 true 時要使用的 Markdown 連結。 |

**傳回值:**
boolean