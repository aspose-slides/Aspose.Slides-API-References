---
title: IHtmlGenerator class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator class

Trình tạo HTML.

Kiểu IHtmlGenerator cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Trả về kích thước ảnh slide.<br/>            Chỉ đọc [`SizeF`](/slides/python-net/vi/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Trả về đơn vị mà kích thước ảnh slide được chỉ định.<br/>            Chỉ đọc [`SvgCoordinateUnit`](/slides/python-net/vi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Trả về mã css của đơn vị mà kích thước ảnh slide được chỉ định.<br/>            Chỉ đọc **str**. |
| [`previous_slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Trả về chỉ số của slide đã được render trước đó hoặc -1 nếu đang render slide đầu tiên.<br/>            Chỉ đọc **int**. |
| [`slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_index/) | Trả về chỉ số của slide đang được render.<br/>            Chỉ đọc **int**. |
| [`next_slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Trả về chỉ số của slide sẽ được render sau slide hiện tại hoặc -1 nếu hiện đang render slide cuối cùng.<br/>            Chỉ đọc **int**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#str) | Thêm văn bản HTML đã định dạng. |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Thêm văn bản HTML đã định dạng. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Thêm văn bản HTML đã định dạng. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#str) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Các dấu xuống dòng và khoảng trắng không được thay thế. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Các dấu xuống dòng và khoảng trắng không được thay thế. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Các dấu xuống dòng và khoảng trắng không được thay thế. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Trích dẫn giá trị thuộc tính và thêm nó vào tệp html. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Trích dẫn giá trị thuộc tính và thêm nó vào tệp html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Trích dẫn giá trị thuộc tính và thêm nó vào tệp html. |


### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)