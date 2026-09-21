---
title: MathElementBase class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase lớp

Lớp cơ sở cho IMathElement với việc triển khai một số phương thức chung cho tất cả các lớp kế thừa  
Chỉ dùng cho nội bộ.  
Lớp kế thừa phải là IMathElement.

Kiểu MathElementBase cung cấp các thành viên sau:

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Ghép một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/join/#str) | Ghép một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/divide/#str) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự đã chỉ định như dấu ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Lấy một hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/function/#str) | Lấy một hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Lấy hàm đã chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Lấy hàm đã chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm đã chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm đã chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm đã chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Xác định căn bậc của độ đã cho từ đối số đã chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/radical/#str) | Xác định căn bậc của độ đã cho từ đối số đã chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/group/#) | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn phía dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/accent/#char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            hoạt động như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### Xem thêm
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)