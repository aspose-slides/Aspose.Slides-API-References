---
title: IMathElement class
second_title: Tài liệu tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/imathelement/
---
## IMathElement lớp

Giao diện cơ bản của bất kỳ phần tử toán học nào: 
            fraction, mathmatical text, function, expression with multiple elements etc

Kiểu IMathElement cung cấp các thành viên sau:

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/join/#imathelement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/join/#str) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/divide/#imathelement) | Tạo một phân số với tử này và mẫu được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/divide/#str) | Tạo một phân số với tử này và mẫu được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử này và mẫu được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử này và mẫu được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/enclose/#) | Bao quanh một phần tử toán học trong dấu ngoặc |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/enclose/#char-char) | Bao quanh phần tử này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/function/#imathelement) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/function/#str) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/radical/#imathelement) | Xác định căn bậc của độ đã cho từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/radical/#str) | Xác định căn bậc của độ đã cho từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Nhận giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Nhận giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Nhận giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Nhận giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-độ |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-độ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Nhận tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Nhận tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Nhận tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/get_children/#) | Lấy các phần tử con |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/accent/#char) | Đặt dấu phụ (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathelement/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được dùng để nhóm các thành phần của một phương trình hoặc một đoạn văn bản toán học khác.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |


### Xem thêm
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)