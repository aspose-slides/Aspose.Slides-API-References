---
title: write_shape_start method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo hình ảnh slide hiện tại sẽ kết thúc, đoạn html được thêm sẽ được chèn và hình ảnh mới sẽ được bắt đầu trên hình ảnh trước đó.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [`IShape`](/slides/python-net/vi/aspose.slides/ishape) | Shape sẽ được render. |

### Xem thêm
* lớp [`EmbedAllFontsHtmlController`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller)
* lớp [`IHtmlGenerator`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator)
* lớp [`IShape`](/slides/python-net/vi/aspose.slides/ishape)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)