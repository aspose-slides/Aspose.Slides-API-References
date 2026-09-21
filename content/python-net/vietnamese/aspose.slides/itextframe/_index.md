---
title: ITextFrame class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/itextframe/
---
## ITextFrame lớp

Biểu diễn một TextFrame.

Kiểu ITextFrame cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`paragraphs`](/slides/python-net/vi/aspose.slides/itextframe/paragraphs/) | Trả về danh sách tất cả các đoạn trong khung.<br/>            Chỉ đọc [`IParagraphCollection`](/slides/python-net/vi/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/vi/aspose.slides/itextframe/text/) | Lấy hoặc đặt văn bản đơn giản cho một TextFrame.<br/>            Đọc/ghi **str**. |
| [`text_frame_format`](/slides/python-net/vi/aspose.slides/itextframe/text_frame_format/) | Trả về đối tượng định dạng cho đối tượng TextFrame này.<br/>            Chỉ đọc [`ITextFrameFormat`](/slides/python-net/vi/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/itextframe/hyperlink_queries/) | Cung cấp quyền truy cập dễ dàng vào các siêu liên kết được chứa.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/vi/aspose.slides/itextframe/parent_shape/) | Trả về hình dạng cha hoặc None nếu đối tượng cha không triển khai giao diện IShape<br/>            Chỉ đọc [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/vi/aspose.slides/itextframe/parent_cell/) | Trả về ô cha hoặc None nếu đối tượng cha không triển khai giao diện ICell.<br/>            Chỉ đọc [`ICell`](/slides/python-net/vi/aspose.slides/icell). |
| [`slide`](/slides/python-net/vi/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/itextframe/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Tô sáng tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Tô sáng tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Tô sáng tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Tô sáng tất cả các kết quả khớp của biểu thức chính quy bằng màu đã chỉ định. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/vi/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Tô sáng tất cả các kết quả khớp của biểu thức chính quy bằng màu đã chỉ định. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Ghép các đoạn có cùng định dạng trong tất cả các đoạn văn. |
| [`split_text_by_columns(self)`](/slides/python-net/vi/aspose.slides/itextframe/split_text_by_columns/#) | Tách nội dung văn bản của [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe) thành một mảng các chuỗi, <br/>            trong đó mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/vi/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Thay thế tất cả các lần xuất hiện của văn bản được chỉ định bằng một văn bản khác được chỉ định. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/vi/aspose.slides/itextframe/replace_regex/#str-str) | Thay thế tất cả các kết quả khớp của biểu thức chính quy bằng chuỗi đã chỉ định. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)