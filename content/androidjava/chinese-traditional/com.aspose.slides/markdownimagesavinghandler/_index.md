---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示 ImageSavingDelegate.ImageSavingDelegate 事件的 markdown 圖像保存處理程序。
type: docs
url: /zh-hant/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

表示 \#ImageSavingDelegate.ImageSavingDelegate 事件的 markdown 圖像保存處理程序。
## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | 在 Markdown 匯出期間，對每個非 SVG 圖像（位圖或圖元文件）調用。 |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

在 Markdown 匯出期間，對每個非 SVG 圖像（位圖或圖元文件）調用。返回 true 以使用指定的鏈結，或返回 false 以套用預設的保存邏輯。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 正在匯出的圖像（位圖或圖元文件）。 |
| format | int | 圖像格式。 |
| link | java.lang.String[] | 返回 true 時使用的 Markdown 連結。 |

**傳回值:**
boolean