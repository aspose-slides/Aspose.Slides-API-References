---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /vi/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Đại diện cho trình xử lý lưu ảnh SVG markdown của sự kiện \#SvgImageSavingDelegate.SvgImageSavingDelegate.

## Methods

| Phương thức | Mô tả |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Được gọi cho mỗi hình ảnh SVG trong quá trình xuất Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Được gọi cho mỗi hình ảnh SVG trong quá trình xuất Markdown. Trả về true để sử dụng liên kết được chỉ định, hoặc false để áp dụng logic lưu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Hình ảnh SVG đang được xuất. |
| link | java.lang.String[] | Liên kết Markdown sẽ được sử dụng khi trả về true. |

**Giá trị trả về:**
boolean