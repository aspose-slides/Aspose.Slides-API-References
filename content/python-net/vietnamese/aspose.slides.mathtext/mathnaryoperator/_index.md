---
title: MathNaryOperator class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator lớp

Xác định một đối tượng toán học N-ary, chẳng hạn như Tổng và Tích phân. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ của các toán tử N-ary bao gồm: Tổng, Hợp, Giao, Tích phân

**Kế thừa:**[`MathNaryOperator`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathNaryOperator cung cấp các thành viên sau:

## Các hàm khởi tạo

| Constructor | Description |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |

## Thuộc tính

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/base/) | Đối số cơ sở |
| [`subscript`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/subscript/) | Chỉ định một đối số chỉ số dưới, ví dụ trong trường hợp tích phân, thiết lập giới hạn dưới |
| [`superscript`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/superscript/) | Chỉ định một đối số chỉ số trên, ví dụ trong trường hợp tích phân, thiết lập giới hạn trên |
| [`operator`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/operator/) | Ký tự toán tử N-ary<br/>            Ví dụ: '∑', '∫' |
| [`limit_location`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Vị trí của các giới hạn (chỉ số dưới và chỉ số trên) |
| [`grow_to_match_operand_height`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Ký tự toán tử mở rộng theo chiều dọc để khớp với chiều cao của toán hạng |
| [`hide_subscript`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Ẩn chỉ số dưới |
| [`hide_superscript`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Ẩn chỉ số trên |

## Phương thức

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/join/#str) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Bao quanh một phần tử toán học trong dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc đơn hoặc các ký tự khác như khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Lấy một hàm của một đối số sử dụng đối tượng này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/function/#str) | Lấy một hàm của một đối số sử dụng đối tượng này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Lấy hàm được chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Lấy hàm được chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm được chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm được chỉ định sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm được chỉ định sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Xác định căn bậc toán học của cấp độ cho trước từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Xác định căn bậc toán học của cấp độ cho trước từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/group/#) | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Đặt dấu nhấn (một ký tự ở trên cùng của phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Đặt một thanh ngang trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Đặt một thanh ngang dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác.<br/>            Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            đóng vai trò là điểm ngắt dòng, hoặc được nhóm lại sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathNaryOperator`](/slides/python-net/vi/aspose.slides.mathtext/mathnaryoperator)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)