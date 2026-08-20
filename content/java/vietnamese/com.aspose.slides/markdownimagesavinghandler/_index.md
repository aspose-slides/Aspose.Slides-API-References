---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho trình xử lý lưu ảnh markdown của sự kiện ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /vi/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Đại diện cho trình xử lý lưu ảnh markdown của sự kiện ImageSavingDelegate.ImageSavingDelegate.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Được gọi cho mỗi hình ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Được gọi cho mỗi hình ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. Trả về true để sử dụng liên kết đã chỉ định, hoặc false để áp dụng logic lưu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hình ảnh đang được xuất (bitmap hoặc metafile). |
| format | int | Định dạng ảnh. |
| link | java.lang.String[] | Liên kết Markdown sẽ được sử dụng khi trả về true. |

**Kết quả trả về:**
boolean