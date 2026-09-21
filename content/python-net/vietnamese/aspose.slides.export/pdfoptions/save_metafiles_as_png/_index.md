---
title: save_metafiles_as_png property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png thuộc tính
true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang ảnh PNG.
            Đọc/ghi **bool**.

### Ghi chú

Mặc định là **true** .
            Tài liệu Pdf có thể chứa đồ họa vector và hình raster. 
            Nếu SaveMetafilesAsPng được đặt thành true thì ảnh Metafile nguồn sẽ được chuyển đổi sang định dạng Png và lưu vào Pdf dưới dạng hình raster. Nếu SaveMetafilesAsPng được đặt thành false thì Metafile nguồn sẽ được chuyển đổi thành đồ họa vector Pdf. Mỗi phương pháp đều có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển đổi sang PNG, thì có thể xảy ra một số mất chất lượng khi thu phóng tài liệu kết quả. Nếu Metafile được chuyển đổi thành đồ họa vector Pdf, thì có thể gặp vấn đề về hiệu năng trong công cụ xem Pdf.

### Định nghĩa:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Xem thêm
* lớp [`PdfOptions`](/slides/python-net/vi/aspose.slides.export/pdfoptions)
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)