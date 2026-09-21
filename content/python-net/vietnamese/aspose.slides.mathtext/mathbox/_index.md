---
title: MathBox class
second_title: Aspose.Slides cho Python thông qua tài liệu tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathbox/
---
## MathBox lớp

Specifies the logical boxing (packaging) of mathematical element.
            Ví dụ, một đối tượng đã được đóng hộp có thể hoạt động như một bộ giả lập toán tử có hoặc không có điểm căn chỉnh, 
            hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong.
            Ví dụ, toán tử "==" nên được đóng hộp để ngăn ngắt dòng.

**Kế thừa:**[`MathBox`](/slides/python-net/vi/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathBox cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Khởi tạo MathBox với phần tử được chỉ định làm đối số |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/base/) | Đối số cơ sở |
| [`operator_emulator`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/operator_emulator/) | Bộ giả lập toán tử.<br/>            Khi true, hộp và nội dung của nó hành xử như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. <br/>            Điều này có nghĩa là, ví dụ, ký tự có thể hoạt động như một điểm ngắt dòng và có thể căn chỉnh với các toán tử khác.<br/>            Các bộ giả lập toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp để tạo thành một toán tử, chẳng hạn như '=='.<br/>            Giá trị mặc định: false |
| [`no_break`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/no_break/) | Không ngắt<br/>            Thuộc tính này chỉ định tính "không thể ngắt" trên hộp đối tượng. Khi true, không có ngắt dòng nào xảy ra bên trong hộp.<br/>            Điều này có thể quan trọng đối với các bộ giả lập toán tử gồm hơn một toán tử nhị phân.<br/>            Khi phần tử này không được chỉ định, ngắt dòng có thể xảy ra bên trong hộp.<br/>            Mặc định: true |
| [`differential`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/differential/) | Vi phân<br/>            Khi true, hộp hoạt động như một vi phân (ví dụ, 𝑑𝑥 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học.<br/>            Mặc định: false |
| [`alignment_point`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/alignment_point/) | Khi true, bộ giả lập toán tử này hoạt động như một điểm căn chỉnh; nghĩa là, <br/>            các điểm căn chỉnh được chỉ định trong các phương trình khác có thể căn chỉnh với nó.<br/>            Mặc định: false |
| [`explicit_break`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/explicit_break/) | Ngắt rõ ràng chỉ định có ngắt dòng ở đầu đối tượng Box hay không, <br/>            sao cho dòng được gói lại ở đầu hộp.<br/>            Xác định số thứ tự của toán tử trên dòng trước của văn bản toán học sẽ<br/>            được sử dụng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học<br/>            các giá trị khả dụng: 1..255<br/>            Mặc định: 0 (không có ngắt rõ ràng) |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/join/#imathelement) | Nối một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/join/#str) | Nối một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/function/#imathelement) | Nhận một hàm của một đối số, sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/function/#str) | Nhận một hàm của một đối số, sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Nhận hàm được chỉ định, sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Nhận hàm được chỉ định, sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Nhận hàm được chỉ định, sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nhận hàm được chỉ định, sử dụng thể hiện này làm đối số và nhận đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nhận hàm được chỉ định, sử dụng thể hiện này làm đối số và nhận đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/radical/#imathelement) | Xác định căn bậc của độ bậc đã cho từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/radical/#str) | Xác định căn bậc của độ bậc đã cho từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Nhận giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Nhận giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Nhận giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Nhận giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Nhận tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Nhận tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Nhận tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/group/#) | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/accent/#char) | Đặt dấu phụ (một ký tự ở trên cùng của phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/overbar/#) | Đặt một thanh ở trên cùng của phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/underbar/#) | Đặt một thanh ở dưới cùng của phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/to_box/#) | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các trường hợp khác của văn bản toán học.<br/>            Một đối tượng đã đóng hộp có thể (ví dụ) hoạt động như một bộ giả lập toán tử có hoặc không có điểm căn chỉnh, <br/>            hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathbox/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathBox`](/slides/python-net/vi/aspose.slides.mathtext/mathbox)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)