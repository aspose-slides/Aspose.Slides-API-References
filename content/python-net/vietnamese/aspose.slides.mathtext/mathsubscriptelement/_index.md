---
title: MathSubscriptElement class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathsubscriptelement/
---
## Lớp MathSubscriptElement

Xác định đối tượng chỉ số dưới, bao gồm một cơ sở và một chỉ số dưới có kích thước giảm, đặt phía dưới và phía bên phải.

**Kế thừa:**[`MathSubscriptElement`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/vi/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathSubscriptElement cung cấp các thành viên sau:

## Hàm khởi tạo

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Khởi tạo một thể hiện mới của lớp MathSubscriptElement. |

## Thuộc tính

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/base/) | Đối số cơ sở |
| [`subscript`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Chỉ số dưới |

## Phương thức

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Đặt một phần tử toán học trong dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Đặt một phần tử toán học trong các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Lấy một hàm của đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Lấy một hàm của đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và thêm một đối số được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và thêm một đối số được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác.<br/>            Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`BaseScript`](/slides/python-net/vi/aspose.slides.mathtext/basescript)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathSubscriptElement`](/slides/python-net/vi/aspose.slides.mathtext/mathsubscriptelement)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)