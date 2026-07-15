---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho trình xử lý lưu ảnh SVG markdown của sự kiện SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /vi/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Đại diện cho trình xử lý lưu ảnh SVG markdown của \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## Methods

| Method | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Được gọi cho mỗi ảnh SVG trong quá trình xuất Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Được gọi cho mỗi ảnh SVG trong quá trình xuất Markdown. Trả về true để sử dụng liên kết đã chỉ định, hoặc false để áp dụng logic lưu mặc định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Ảnh SVG đang được xuất. |
| link | java.lang.String[] | Liên kết Markdown sẽ được sử dụng khi trả về true. |

**Returns:**
boolean