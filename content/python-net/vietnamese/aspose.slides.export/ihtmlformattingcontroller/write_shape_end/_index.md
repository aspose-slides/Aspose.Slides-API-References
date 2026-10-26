---
title: write_shape_end method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, quá trình tạo hình ảnh slide hiện tại sẽ kết thúc, đoạn html đã thêm sẽ được chèn và hình ảnh mới sẽ được bắt đầu trên hình ảnh trước.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [`IShape`](/slides/python-net/vi/aspose.slides/ishape) | Shape được render cuối cùng. |



### Xem thêm
* lớp [`IHtmlFormattingController`](/slides/python-net/vi/aspose.slides.export/ihtmlformattingcontroller)
* lớp [`IHtmlGenerator`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator)
* lớp [`IShape`](/slides/python-net/vi/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)