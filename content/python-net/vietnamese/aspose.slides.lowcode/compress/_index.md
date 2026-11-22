---
title: Compress class
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/compress/
---
## Lớp Compress

Đại diện cho một nhóm các phương thức nhằm nén [`Presentation`](/slides/python-net/vi/aspose.slides/presentation).

Kiểu Compress cung cấp các thành viên sau:

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/vi/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Giảm kích thước của một bản trình bày bằng cách áp dụng tất cả các bước nén có sẵn:<br/>            <br/>* Xóa các slide master không dùng **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Xóa các slide bố cục không dùng **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Giữ lại chỉ các glyph thực sự được sử dụng trong phông chữ nhúng **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Giảm độ phân giải ảnh xuống 150 DPI và xóa các khu vực đã cắt của ảnh **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/vi/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Thực hiện nén [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) bằng cách xóa các slide master không dùng. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/vi/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Thực hiện nén [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) bằng cách xóa các slide bố cục không dùng. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/vi/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Thực hiện nén [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) bằng cách xóa các ký tự không dùng khỏi phông chữ nhúng. |
| [`compress_images(presentation, resolution)`](/slides/python-net/vi/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Giảm độ phân giải của ảnh trong bản trình bày và xóa các khu vực đã cắt của chúng,<br/>            tương tự như “Compress Pictures” của PowerPoint được áp dụng cho tất cả ảnh.<br/>            Ảnh trên slide, slide bố cục và slide master sẽ được xử lý, bao gồm cả ảnh bên trong các hình nhóm<br/>            và ảnh nền của các hình. |


### Xem Thêm
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* mô-đun [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* thư viện [`Aspose.Slides`](/slides/python-net)