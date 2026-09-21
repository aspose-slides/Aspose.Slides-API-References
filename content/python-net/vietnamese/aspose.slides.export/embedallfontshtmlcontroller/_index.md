---
title: EmbedAllFontsHtmlController class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController lớp

Lớp bộ điều khiển định dạng dùng để nhúng tất cả phông chữ của bản trình chiếu ở định dạng WOFF.

Kiểu EmbedAllFontsHtmlController cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Tạo một thể hiện mới |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Tạo một thể hiện mới |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Được gọi để ghi phần đầu tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Được gọi để ghi phần cuối tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Được gọi để ghi phần đầu slide html. Được gọi một lần cho mỗi slide. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Được gọi để ghi phần cuối slide html. Được gọi một lần cho mỗi slide. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Được gọi trước khi vẽ shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo ảnh slide hiện tại sẽ kết thúc, đoạn html được thêm sẽ được chèn và ảnh mới sẽ bắt đầu trên ảnh trước. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Được gọi trước khi vẽ shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo ảnh slide hiện tại sẽ kết thúc, đoạn html được thêm sẽ được chèn và ảnh mới sẽ bắt đầu trên ảnh trước. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Ghi tất cả phông chữ có trong [`Presentation`](/slides/python-net/vi/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/vi/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Ghi dữ liệu dưới dạng base64 vào chính tài liệu HTML |

### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)