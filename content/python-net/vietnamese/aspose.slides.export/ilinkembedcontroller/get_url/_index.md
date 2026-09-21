---
title: get_url method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Trả về một URL đến một đối tượng bên ngoài.
            Phương thức này luôn được gọi nếu **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** trả về [`LinkEmbedDecision.LINK`](/slides/python-net/vi/aspose.slides.export/linkembeddecision/LINK) và có thể được gọi nếu **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** trả về [`LinkEmbedDecision.EMBED`](/slides/python-net/vi/aspose.slides.export/linkembeddecision/EMBED) nhưng không thể nhúng.
            Có thể được gọi nhiều lần cho cùng một id đối tượng.

### Trả về

URL của đối tượng bên ngoài hoặc None nếu đối tượng này nên bị bỏ qua.



```python
def get_url(self, id, referrer):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| id | **int** | Id đối tượng. Id này là duy nhất trong toàn bộ hoạt động lưu. |
| referrer | **int** | Id của đối tượng tham chiếu hoặc 0, nếu đối tượng được tham chiếu bởi tài liệu gốc. Có thể được sử dụng để tạo liên kết tương đối. |



### Xem thêm
* lớp [`ILinkEmbedController`](/slides/python-net/vi/aspose.slides.export/ilinkembedcontroller)
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)