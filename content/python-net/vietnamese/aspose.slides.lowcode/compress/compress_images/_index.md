---
title: compress_images method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Giảm độ phân giải của hình ảnh trong bài thuyết trình và xóa các khu vực đã cắt, tương tự như tính năng "Compress Pictures" của PowerPoint được áp dụng cho tất cả hình ảnh. Hình ảnh trên các slide, slide bố cục và slide chủ đề được xử lý, bao gồm cả hình ảnh trong nhóm hình và các nền ảnh của hình dạng.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) | Bài thuyết trình cần xử lý. |
| resolution | [`PicturesCompression`](/slides/python-net/vi/aspose.slides.export/picturescompression) | Độ phân giải mục tiêu tương đối với kích thước mà mỗi hình ảnh được hiển thị.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/vi/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) giữ nguyên hình ảnh. |

### Ghi chú

Các hình ảnh đã ở mức độ phân giải mục tiêu hoặc thấp hơn sẽ không bị thay đổi; hình ảnh không bao giờ được phóng to.

Không được xử lý: nền slide, nền ô bảng, biểu đồ, SmartArt, ảnh GIF (để bảo tồn hoạt ảnh), ảnh SVG và ảnh metafile (EMF/WMF).

Các khu vực đã cắt sẽ bị xóa vĩnh viễn và không thể khôi phục trong PowerPoint.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` là `None`. |

### Xem thêm
* lớp [`Compress`](/slides/python-net/vi/aspose.slides.lowcode/compress)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* liệt kê [`PicturesCompression`](/slides/python-net/vi/aspose.slides.export/picturescompression)
* module [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* thư viện [`Aspose.Slides`](/slides/python-net)