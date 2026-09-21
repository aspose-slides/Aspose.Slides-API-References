---
title: save_metafiles_as_png property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png thuộc tính
True để chuyển đổi tất cả các metafile được sử dụng trong một bản trình bày sang các hình ảnh PNG.  
Đọc/ghi **bool**.

### Ghi chú

Mặc định là **true**.  
Tài liệu Pdf có thể chứa đồ họa vector và hình ảnh raster.  
Nếu SaveMetafilesAsPng được đặt thành true thì hình ảnh Metafile nguồn sẽ được chuyển đổi sang định dạng Png và lưu vào Pdf dưới dạng hình raster.  
Nếu SaveMetafilesAsPng được đặt thành false thì Metafile nguồn sẽ được chuyển đổi sang đồ họa vector Pdf.  
Mỗi cách tiếp cận có ưu và nhược điểm.  
Ví dụ, nếu Metafile được chuyển đổi sang PNG, thì một số mất chất lượng có thể xảy ra khi thu phóng tài liệu kết quả.  
Nếu Metafile được chuyển đổi sang đồ họa vector Pdf, thì có thể gặp vấn đề về hiệu suất trong công cụ xem Pdf.

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
* lớp [`IPdfOptions`](/slides/python-net/vi/aspose.slides.export/ipdfoptions)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)