---
title: MathematicalText class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText lớp

Văn bản toán học

**Kế thừa:**[`MathematicalText`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathematicalText cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/__init__/#) | Constructor mặc định (tạo giá trị String.Empty) |
| [`__init__(self, math_symbol)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/__init__/#char) | Tạo MathText với một ký hiệu đơn |
| [`__init__(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/__init__/#str) | Tạo MathematicalText từ văn bản |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | Tạo MathematicalText từ văn bản và cài đặt định dạng |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`value`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/value/) | Giá trị văn bản |
| [`format`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/format/) | Thuộc tính định dạng văn bản |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Kết nối một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/join/#str) | Kết nối một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/divide/#str) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự đã chỉ định như dấu ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Lấy một hàm của một đối số sử dụng đối tượng này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/function/#str) | Lấy một hàm của một đối số sử dụng đối tượng này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | Lấy hàm đã chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | Lấy hàm đã chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm đã chỉ định sử dụng đối tượng này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm đã chỉ định sử dụng đối tượng này làm đối số và bổ sung đối số đã chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm đã chỉ định sử dụng đối tượng này làm đối số và bổ sung đối số đã chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Xác định căn bậc n toán học từ đối số đã chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/radical/#str) | Xác định căn bậc n toán học từ đối số đã chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Đặt phần tử này vào một khung biên |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một khung biên |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/accent/#char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc một ví dụ khác của văn bản toán học.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### Xem Thêm
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathematicalText`](/slides/python-net/vi/aspose.slides.mathtext/mathematicaltext)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)