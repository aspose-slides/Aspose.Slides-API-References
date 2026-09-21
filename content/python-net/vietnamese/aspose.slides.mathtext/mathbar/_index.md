---
title: MathBar class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathbar/
---
## MathBar lớp

Chỉ định hàm thanh, bao gồm một đối số cơ sở và một thanh trên hoặc thanh dưới

**Inheritance:**[`MathBar`](/slides/python-net/vi/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathBar cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Khởi tạo MathBar với thanh trên (vị trí Top) |
| [`__init__(self, element, position)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Khởi tạo MathBar với vị trí được chỉ định |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/base/) | Đối số cơ sở |
| [`position`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/position/) | Vị trí của đường thanh.<br/>            Mặc định: Top |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/join/#imathelement) | Nối một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/join/#str) | Nối văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/enclose/#) | Bao quanh phần tử toán học trong ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/enclose/#char-char) | Bao quanh phần tử toán học trong các ký tự được chỉ định như ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/function/#imathelement) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/function/#str) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số và đối số phụ được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nhận hàm được chỉ định sử dụng thể hiện này làm đối số và đối số phụ được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/radical/#imathelement) | Xác định căn bậc của số đã cho từ đối số được chỉ định |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/radical/#str) | Xác định căn bậc của số đã cho từ đối số được chỉ định |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Nhận giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Nhận giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Nhận giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Nhận giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Nhận tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Nhận tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Nhận tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/accent/#char) | Đặt dấu nhấn (ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/overbar/#) | Đặt thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/underbar/#) | Đặt thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic)<br/>            được dùng để nhóm các thành phần của một phương trình hoặc văn bản toán học khác.<br/>            Một đối tượng đóng hộp có thể (ví dụ) đóng vai trò là một bộ giả lập toán tử có hoặc không có điểm căn chỉnh,<br/>            làm điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbar/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathBar`](/slides/python-net/vi/aspose.slides.mathtext/mathbar)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)