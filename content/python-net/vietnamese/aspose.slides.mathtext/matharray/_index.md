---
title: MathArray class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/matharray/
---
## MathArray lớp

Xác định một mảng dọc các phương trình hoặc bất kỳ đối tượng toán học nào

**Kế thừa:**[`MathArray`](/slides/python-net/vi/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathArray cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/__init__/#imathelement) | Tạo một mảng toán học và đặt phần tử đã chỉ định vào trong |
| [`__init__(self, elements)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`arguments`](/slides/python-net/vi/aspose.slides.mathtext/matharray/arguments/) | Tập hợp các mục của mảng |
| [`base_justification`](/slides/python-net/vi/aspose.slides.mathtext/matharray/base_justification/) | Xác định cách căn chỉnh của mảng so với văn bản xung quanh<br/>            Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, đầu hoặc trung tâm của đối tượng mảng.<br/>            Giá trị mặc định: Center |
| [`maximum_distribution`](/slides/python-net/vi/aspose.slides.mathtext/matharray/maximum_distribution/) | Phân phối tối đa<br/>            Khi đúng, mảng được giãn đến chiều rộng tối đa của phần tử chứa (trang, cột, ô, vv.). |
| [`object_distribution`](/slides/python-net/vi/aspose.slides.mathtext/matharray/object_distribution/) | Phân phối đối tượng<br/>            Khi đúng, nội dung của mảng được giãn đến chiều rộng tối đa của đối tượng mảng. |
| [`row_spacing_rule`](/slides/python-net/vi/aspose.slides.mathtext/matharray/row_spacing_rule/) | Kiểu khoảng cách dọc giữa các phần tử mảng<br/>            Mặc định: SingleLineGap |
| [`row_spacing`](/slides/python-net/vi/aspose.slides.mathtext/matharray/row_spacing/) | Khoảng cách giữa các hàng của mảng<br/>            Chỉ được dùng khi RowSpacingRule được đặt thành 3 Exactly, trong trường hợp này đơn vị đo là điểm<br/>            hoặc Multiple, trong trường hợp này đơn vị đo là nửa dòng.<br/>            Mặc định: 0 |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/join/#imathelement) | Nối một phần tử toán học và tạo thành một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/join/#str) | Nối một văn bản toán học và tạo thành một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/divide/#str) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự đã chỉ định như dấu ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/function/#imathelement) | Nhận một hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/function/#str) | Nhận một hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Nhận hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Nhận hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Nhận hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nhận hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nhận hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/radical/#imathelement) | Xác định căn bậc toán học của độ bậc đã cho từ đối số đã chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/radical/#str) | Xác định căn bậc toán học của độ bậc đã cho từ đối số đã chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Nhận giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Nhận giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Nhận giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Nhận giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-độ |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-độ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Nhận tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Nhận tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Nhận tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/to_border_box/#) | Đặt phần tử này vào một khung biên |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một khung biên |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/accent/#char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được dùng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác.<br/>            Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/matharray/get_children/#) | Lấy các phần tử con |


### Xem thêm
* lớp [`MathArray`](/slides/python-net/vi/aspose.slides.mathtext/matharray)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)