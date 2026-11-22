---
title: compress_presentation method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Giảm kích thước của bản trình chiếu bằng cách áp dụng tất cả các bước nén có sẵn:
            
* Xóa các slide chủ không sử dụng **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Xóa các slide bố trí không sử dụng **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Giữ lại chỉ các glyph thực sự được sử dụng trong phông chữ nhúng **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Giảm độ phân giải hình ảnh xuống 150 DPI và xóa các vùng đã cắt của hình ảnh **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình chiếu cần nén. |

### Ghi chú

Để tùy chỉnh quá trình nén, ví dụ để sử dụng độ phân giải hình ảnh khác hoặc bỏ qua một bước, hãy gọi các phương thức được liệt kê ở trên riêng lẻ thay vì phương thức này. Các vùng đã cắt của hình ảnh sẽ bị xóa vĩnh viễn và không thể khôi phục trong PowerPoint.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` là `None`. |



### Xem thêm
* lớp [`Compress`](/slides/python-net/vi/aspose.slides.lowcode/compress)
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* mô-đun [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* thư viện [`Aspose.Slides`](/slides/python-net)