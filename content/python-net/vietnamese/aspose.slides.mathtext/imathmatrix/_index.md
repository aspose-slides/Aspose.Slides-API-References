---
title: IMathMatrix class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix lớp

Xác định đối tượng Matrix, bao gồm các phần tử con sắp xếp thành một hoặc nhiều hàng và cột. 
            Cần lưu ý rằng ma trận không có dấu phân cách tích hợp. 
            Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng phân cách (IMathDelimiter).
            Các đối số null có thể được dùng để tạo khoảng trống trong ma trận.

Kiểu IMathMatrix cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`row_count`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/row_count/) | Số hàng trong ma trận |
| [`column_count`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/column_count/) | Số cột trong ma trận |
| [`hide_placeholders`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Ẩn các vị trí giữ chỗ cho các phần tử ma trận trống<br/>            Mặc định: false |
| [`base_justification`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/base_justification/) | Xác định căn chỉnh dọc so với văn bản xung quanh. <br/>            Các giá trị có thể là top, bottom, và center.<br/>            Mặc định: Center |
| [`min_column_width`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/min_column_width/) | Chiều rộng tối thiểu của cột tính bằng twips (1/20 điểm)<br/>            Khoảng cách khoảng trống (còn gọi là “Column Gap” hoặc “Gap Width”) được cộng vào <br/>            MinColumnWidth để xác định tổng khoảng cách cột ma trận<br/>            (khoảng cách giữa các cạnh tương tự của các cột khác nhau).<br/>            Mặc định: 0. |
| [`column_gap_rule`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Kiểu khoảng cách ngang giữa các cột của ma trận; <br/>            Đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twips).<br/>            Mặc định: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/column_gap/) | Giá trị của khoảng cách ngang giữa các cột của ma trận;<br/>            Nếu ColumnGapRule được đặt thành 3 ("Exactly"), thì đơn vị được hiểu là twips (1/20 điểm)<br/>            Nếu ColumnGapRule được đặt thành 4 ("Multiple"), thì đơn vị được hiểu là số lần tăng 0.5 em.<br/>            Trong các trường hợp khác bị bỏ qua.<br/>            Mặc định: 0 |
| [`row_gap_rule`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Kiểu khoảng cách dọc giữa các hàng của ma trận; <br/>            Đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twips).<br/>            Mặc định: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/row_gap/) | Giá trị của khoảng cách dọc giữa các hàng của ma trận;<br/>            Nếu RowGapRule được đặt thành 3 ("Exactly"), thì đơn vị được hiểu là twips (1/20 điểm)<br/>            Nếu RowGapRule được đặt thành 4 ("Multiple"), thì đơn vị được hiểu là half-lines.<br/>            Mặc định: 0 |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Lấy căn chỉnh ngang của cột được chỉ định |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Đặt căn chỉnh ngang của cột được chỉ định |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Đặt căn chỉnh ngang của các cột được chỉ định |
| [`insert_row_before(self, row_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Chèn một hàng mới trước hàng được chỉ định<br/>            Ban đầu tất cả các phần tử trong hàng mới đều là None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Chèn một hàng mới sau hàng được chỉ định<br/>            Ban đầu tất cả các phần tử trong hàng mới đều là None. |
| [`delete_row(self, row_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Xóa hàng được chỉ định |
| [`insert_column_before(self, column_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Chèn một cột mới trước cột được chỉ định<br/>            Ban đầu tất cả các phần tử trong cột mới đều là None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Chèn một cột mới sau cột được chỉ định<br/>            Ban đầu tất cả các phần tử trong cột mới đều là None. |
| [`delete_column(self, column_index)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Xóa cột được chỉ định |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Xem thêm
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)