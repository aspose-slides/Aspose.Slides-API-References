---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho bộ xử lý lưu ảnh markdown của sự kiện ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /vi/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Đại diện cho bộ xử lý lưu ảnh markdown của sự kiện #ImageSavingDelegate.ImageSavingDelegate.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Được gọi cho mỗi ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Được gọi cho mỗi ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. Trả về true để sử dụng liên kết được chỉ định, hoặc false để áp dụng logic lưu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Ảnh đang được xuất (bitmap hoặc metafile). |
| format | int | Định dạng ảnh. |
| link | java.lang.String[] | Liên kết Markdown để sử dụng khi trả về true. |

**Trả về:**
boolean