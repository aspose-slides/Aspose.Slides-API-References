---
title: TextFrame class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/textframe/
---
## TextFrame lớp

Biểu diễn một TextFrame.

Kiểu TextFrame cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`paragraphs`](/slides/python-net/vi/aspose.slides/textframe/paragraphs/) | Trả về danh sách tất cả các đoạn văn trong một khung.<br/>            Chỉ đọc [`IParagraphCollection`](/slides/python-net/vi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/vi/aspose.slides/textframe/text/) | Lấy hoặc đặt văn bản thuần cho TextFrame.<br/>            Đọc/ghi **str**. |
| [`text_frame_format`](/slides/python-net/vi/aspose.slides/textframe/text_frame_format/) | Trả về đối tượng định dạng cho đối tượng TextFrame này.<br/>            Chỉ đọc [`ITextFrameFormat`](/slides/python-net/vi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/textframe/hyperlink_queries/) | Cung cấp quyền truy cập dễ dàng tới các siêu liên kết được chứa.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/vi/aspose.slides/textframe/slide/) | Trả về slide cha của TextFrame.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/textframe/presentation/) | Trả về bản trình bày cha của TextFrame.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/vi/aspose.slides/textframe/parent_shape/) | Trả về shape cha hoặc None nếu đối tượng cha không thực thi giao diện IShape<br/>            Chỉ đọc [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/vi/aspose.slides/textframe/parent_cell/) | Trả về cell cha hoặc None nếu đối tượng cha không thực thi giao diện ICell.<br/>            Chỉ đọc [`ICell`](/slides/python-net/vi/aspose.slides/icell). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/vi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/vi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/vi/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/vi/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Tô sáng tất cả các khớp của biểu thức chính quy bằng màu đã chỉ định. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/vi/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Tô sáng tất cả các khớp của biểu thức chính quy bằng màu đã chỉ định. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/textframe/join_portions_with_same_formatting/#) | Nối các run có cùng định dạng trong tất cả các đoạn văn. |
| [`split_text_by_columns(self)`](/slides/python-net/vi/aspose.slides/textframe/split_text_by_columns/#) | Tách nội dung văn bản của [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe) thành một mảng các chuỗi,<br/>            trong đó mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/vi/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Thay thế tất cả các lần xuất hiện của văn bản đã chỉ định bằng một văn bản đã chỉ định khác. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/vi/aspose.slides/textframe/replace_regex/#str-str) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi đã chỉ định. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)