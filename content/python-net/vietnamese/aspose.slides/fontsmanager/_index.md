---
title: FontsManager class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/fontsmanager/
---
## FontsManager lớp

Quản lý phông chữ trên toàn bộ bản trình chiếu.

Kiểu FontsManager cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/vi/aspose.slides/fontsmanager/font_subst_rule_list/) | Các thay thế phông chữ sẽ được sử dụng khi render.<br/>            Đọc/ghi [`IFontSubstRuleCollection`](/slides/python-net/vi/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/vi/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Đại diện cho bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý bộ sưu tập phông chữ cho việc thay thế thích hợp bằng chức năng fallback.<br/>            Đọc/ghi [`IFontFallBackRulesCollection`](/slides/python-net/vi/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/vi/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Xác định xem phông chữ đã đăng ký có nên được ưu tiên hơn phông chữ nhúng có cùng tên và kiểu hay không.<br/>            Khi được bật, các phông chữ nhúng phù hợp sẽ tạm thời được thay thế bằng các phông chữ đã đăng ký tương ứng trong quá trình xuất. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_substitutions/#) | Lấy thông tin về các phông chữ sẽ được thay thế khi render bản trình chiếu. |
| [`get_substitutions(self, slides)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_substitutions/#listint) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình render các slide được chỉ định. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/vi/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Thêm phông chữ nhúng<br/>            Hãy nhớ rằng khi sao chép bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Trước tiên hãy xác định giấy phép của <br/>            một phông chữ và kiểm tra chúng có thể được chuyển tự do sang máy khác hay không. Một ArgumentException có thể được ném nếu dữ liệu phông chữ là None hoặc phông chữ này đã được nhúng |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/vi/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Thêm phông chữ nhúng<br/>            Hãy nhớ rằng khi sao chép bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Trước tiên hãy xác định giấy phép của <br/>            một phông chữ và kiểm tra chúng có thể được chuyển tự do sang máy khác hay không. Một ArgumentException có thể được ném nếu dữ liệu phông chữ là None hoặc phông chữ này đã được nhúng |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/vi/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Thay thế phông chữ trong bản trình chiếu |
| [`replace_font(self, subst_rule)`](/slides/python-net/vi/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong [`FontSubstRule`](/slides/python-net/vi/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/vi/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong bộ sưu tập của [`FontSubstRule`](/slides/python-net/vi/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_fonts/#) | Trả về các phông chữ được sử dụng trong bản trình chiếu |
| [`get_embedded_fonts(self)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_embedded_fonts/#) | Trả về các phông chữ đã nhúng trong bản trình chiếu |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/vi/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Xóa phông chữ nhúng |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Lấy mảng byte đại diện cho dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ được chỉ định. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/vi/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Xác định mức độ nhúng của một phông chữ từ mảng byte và tên phông chữ được cung cấp. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)