---
title: ITextFrame class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/itextframe/
---
## ITextFrame lớp

Đại diện cho một TextFrame.

Kiểu ITextFrame cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`paragraphs`](/slides/python-net/vi/aspose.slides/itextframe/paragraphs/) | Trả về danh sách tất cả các đoạn trong một khung.<br/>            Chỉ đọc [`IParagraphCollection`](/slides/python-net/vi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/vi/aspose.slides/itextframe/text/) | Lấy hoặc đặt văn bản thuần cho một TextFrame.<br/>            Đọc/ghi **str**. |
| [`text_frame_format`](/slides/python-net/vi/aspose.slides/itextframe/text_frame_format/) | Trả về đối tượng định dạng cho đối tượng TextFrame này.<br/>            Chỉ đọc [`ITextFrameFormat`](/slides/python-net/vi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/itextframe/hyperlink_queries/) | Cung cấp truy cập dễ dàng đến các siêu liên kết được chứa.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/vi/aspose.slides/itextframe/parent_shape/) | Trả về hình dạng cha hoặc None nếu đối tượng cha không thực thi giao diện IShape<br/>            Chỉ đọc [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/vi/aspose.slides/itextframe/parent_cell/) | Trả về ô cha hoặc None nếu đối tượng cha không thực thi giao diện ICell.<br/>            Chỉ đọc [`ICell`](/slides/python-net/vi/aspose.slides/icell). |
| [`slide`](/slides/python-net/vi/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/itextframe/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Tô sáng tất cả các khớp của biểu thức chính quy với màu được chỉ định. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Tô sáng tất cả các khớp của biểu thức chính quy với màu được chỉ định. |
| [`get_text_rect(self)`](/slides/python-net/vi/aspose.slides/itextframe/get_text_rect/#) | Lấy hình chữ nhật văn bản được xác định bởi hình học của hình dạng cha. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Ghép các đoạn chạy có cùng định dạng trong tất cả các đoạn. |
| [`split_text_by_columns(self)`](/slides/python-net/vi/aspose.slides/itextframe/split_text_by_columns/#) | Tách nội dung văn bản của [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe) thành một mảng các chuỗi, <br/>            trong đó mỗi phần tử tương ứng với một cột văn bản riêng trong khung. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/vi/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Thay thế tất cả các lần xuất hiện của văn bản đã chỉ định bằng một văn bản đã chỉ định khác. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/vi/aspose.slides/itextframe/replace_regex/#str-str) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định. |

### Xem Thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)