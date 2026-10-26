---
title: ILinkEmbedController class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController lớp

Giao diện callback được sử dụng để xác định cách đối tượng nên được xử lý trong quá trình lưu.

Kiểu ILinkEmbedController cung cấp các thành viên sau:

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/vi/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Xác định vị trí lưu trữ đối tượng.<br/>            Phương pháp này được gọi một lần cho mỗi id đối tượng.<br/>            Không đảm bảo sẽ không có hai đối tượng có cùng dữ liệu, semanticName và contentType nhưng có id khác nhau. |
| [`get_url(self, id, referrer)`](/slides/python-net/vi/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Trả về một URL tới đối tượng bên ngoài.<br/>            Phương pháp này luôn được gọi nếu **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** trả về [`LinkEmbedDecision.LINK`](/slides/python-net/vi/aspose.slides.export/linkembeddecision/LINK) và có thể được gọi nếu **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** trả về [`LinkEmbedDecision.EMBED`](/slides/python-net/vi/aspose.slides.export/linkembeddecision/EMBED) nhưng việc nhúng là không thể.<br/>            Có thể được gọi nhiều lần cho cùng một id đối tượng. |
| [`save_external(self, id, entity_data)`](/slides/python-net/vi/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Lưu đối tượng bên ngoài. |

### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)