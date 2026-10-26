---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /zh-hant/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

代表 \#ImageSavingDelegate.ImageSavingDelegate 事件的 markdown 圖像保存處理程式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | 在 Markdown 匯出期間，對每個非 SVG 圖像（位圖或圖元檔）調用。 |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

在 Markdown 匯出期間，對每個非 SVG 圖像（位圖或圖元檔）調用。傳回 true 以使用指定的連結，或傳回 false 以套用預設的保存邏輯。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 正在匯出的圖像（位圖或圖元檔）。 |
| format | int | 圖像格式。 |
| link | java.lang.String[] | 在返回 true 時要使用的 Markdown 連結。 |

**傳回：**
boolean