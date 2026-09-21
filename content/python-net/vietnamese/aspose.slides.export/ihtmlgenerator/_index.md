---
title: IHtmlGenerator class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator lớp

Trình tạo HTML.

Kiểu IHtmlGenerator cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`slide_image_size`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Returns slide image size.<br/>            Read-only **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            Read-only [`SvgCoordinateUnit`](/slides/python-net/vi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            Read-only **str**. |
| [`previous_slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            Read-only **int**. |
| [`slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            Read-only **int**. |
| [`next_slide_index`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            Read-only **int**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#str) | Adds formatted HTML text. |
| [`add_html(self, html)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Adds formatted HTML text. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Adds formatted HTML text. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#str) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/vi/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Quotes attribute value and adds it to the html file. |

### Xem thêm
* module [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)