---
title: IFontsManager class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ifontsmanager/
---
## IFontsManager lớp

Quản lý phông chữ trong toàn bộ bài thuyết trình.

Kiểu IFontsManager cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/vi/aspose.slides/ifontsmanager/font_subst_rule_list/) | Các thay thế phông chữ để sử dụng khi render<br/>            Đọc/ghi [`IFontSubstRuleCollection`](/slides/python-net/vi/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/vi/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Biểu thị bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ phông chữ nhằm thực hiện việc thay thế phù hợp bằng chức năng dự phòng<br/>            Đọc/ghi [`IFontFallBackRulesCollection`](/slides/python-net/vi/aspose.slides/ifontfallbackrulescollection). |

## Phương thức

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_substitutions/#) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình render bài thuyết trình. |
| [`get_substitutions(self, slides)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_substitutions/#listint) | Lấy thông tin về các phông chữ sẽ được thay thế khi render các slide được chỉ định. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/vi/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Thêm phông chữ được nhúng.<br/>            Hãy nhớ khi sao chép bất kỳ phông chữ nào rằng hầu hết các phông chữ đều có bản quyền. Đầu tiên hãy tìm giấy phép của <br/>            một phông chữ và xác nhận chúng có thể được chuyển sang máy khác một cách tự do. Một ArgumentException có thể được ném nếu dữ liệu phông chữ là None hoặc phông chữ này đã được nhúng |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/vi/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Thêm phông chữ được nhúng<br/>            Hãy nhớ khi thêm bất kỳ phông chữ nào rằng hầu hết các phông chữ đều có bản quyền. Đầu tiên hãy tìm giấy phép của <br/>            một phông chữ và xác nhận chúng có thể được chuyển sang máy khác một cách tự do. Một ArgumentException có thể được ném nếu dữ liệu phông chữ là None hoặc phông chữ này đã được nhúng |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/vi/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Thay thế phông chữ trong bài thuyết trình |
| [`replace_font(self, subst_rule)`](/slides/python-net/vi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong [`IFontSubstRule`](/slides/python-net/vi/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/vi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong bộ sưu tập của [`IFontSubstRule`](/slides/python-net/vi/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_fonts/#) | Trả về các phông chữ được sử dụng trong bài thuyết trình |
| [`get_embedded_fonts(self)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Trả về các phông chữ đã được nhúng trong bài thuyết trình |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/vi/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Xóa phông chữ đã nhúng |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Lấy mảng byte đại diện cho dữ liệu phông chữ cho kiểu phông chữ và dữ liệu phông chữ đã chỉ định. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/vi/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Xác định mức độ nhúng của một phông chữ từ mảng byte và tên phông chữ đã cho. |


### Xem Thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)