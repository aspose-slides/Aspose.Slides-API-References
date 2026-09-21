---
title: MathFraction class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathfraction/
---
## MathFraction lớp

Xác định đối tượng phân số, bao gồm tử và mẫu được ngăn cách bằng dấu gạch phân số. Dấu gạch phân số có thể nằm ngang hoặc chéo, tùy thuộc vào các thuộc tính của phân số. Đối tượng phân số cũng được dùng để biểu diễn hàm chồng, đặt một phần tử lên trên phần tử khác, mà không có dấu gạch phân số.

**Kế thừa:**[`MathFraction`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathFraction cung cấp các thành viên sau:

## Các hàm khởi tạo

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Khởi tạo MathFraction với tử, mẫu và kiểu được chỉ định |
| [`__init__(self, numerator, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Khởi tạo một MathFraction có kiểu 'Bar' với tử và mẫu được chỉ định |

## Thuộc tính

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/fraction_type/) | Kiểu phân số<br/>            Mặc định: Bar |
| [`numerator`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/numerator/) | Tử |
| [`denominator`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/denominator/) | Mẫu |

## Phương thức

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/join/#imathelement) | Ghép một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/join/#str) | Ghép một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Tạo một phân số với tử này và mẫu được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/divide/#str) | Tạo một phân số với tử này và mẫu được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Tạo một phân số có kiểu được chỉ định với tử này và mẫu được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Tạo một phân số có kiểu được chỉ định với tử này và mẫu được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/function/#imathelement) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/function/#str) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/radical/#str) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/group/#) | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn phía dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/to_border_box/#) | Đặt phần tử này trong một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này trong một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/accent/#char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/to_box/#) | Đặt phần tử này trong một hộp không hiển thị (nhóm logic)<br/>            được dùng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh,<br/>            đóng vai trò như một điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathFraction`](/slides/python-net/vi/aspose.slides.mathtext/mathfraction)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)