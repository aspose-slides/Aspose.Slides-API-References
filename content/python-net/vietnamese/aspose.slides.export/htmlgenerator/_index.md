---
title: HtmlGenerator class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator lớp

Trình tạo Html.

Kiểu HtmlGenerator cung cấp các thành viên sau:

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`slide_image_size`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/slide_image_size/) | Trả về kích thước hình ảnh slide.<br/>            Chỉ đọc [`SizeF`](/slides/python-net/vi/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Trả về đơn vị mà kích thước hình ảnh slide được chỉ định.<br/>            Chỉ đọc [`SvgCoordinateUnit`](/slides/python-net/vi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Trả về mã CSS của đơn vị mà kích thước hình ảnh slide được chỉ định.<br/>            Chỉ đọc **str**. |
| [`previous_slide_index`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/previous_slide_index/) | Trả về chỉ mục của slide đã được vẽ trước đó hoặc -1 nếu đang vẽ slide đầu tiên.<br/>            Chỉ đọc **int**. |
| [`slide_index`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/slide_index/) | Trả về chỉ mục của slide hiện đang được vẽ.<br/>            Chỉ đọc **int**. |
| [`next_slide_index`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/next_slide_index/) | Trả về chỉ mục của slide sẽ được vẽ sau slide hiện tại hoặc -1 nếu đang vẽ slide cuối cùng.<br/>            Chỉ đọc **int**. |

## Phương thức

| Method | Mô tả |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_html/#str) | Thêm văn bản HTML có định dạng. |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_html/#listchar) | Thêm văn bản HTML có định dạng. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Thêm văn bản HTML có định dạng. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_text/#str) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Dòng ngắt và khoảng trắng không được thay thế. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_text/#listchar) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Dòng ngắt và khoảng trắng không được thay thế. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html.<br/>            Dòng ngắt và khoảng trắng không được thay thế. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Đánh dấu giá trị thuộc tính và thêm vào tệp html. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Đánh dấu giá trị thuộc tính và thêm vào tệp html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/vi/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Đánh dấu giá trị thuộc tính và thêm vào tệp html. |


### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)