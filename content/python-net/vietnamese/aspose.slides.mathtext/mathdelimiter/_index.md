---
title: MathDelimiter class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter lớp

Xác định đối tượng delimiter, bao gồm các ký tự mở và đóng (như dấu ngoặc tròn, ngoặc nhọn, ngoặc vuông và thanh dọc), và một hoặc nhiều phần tử toán học bên trong, được ngăn cách bằng một ký tự chỉ định. Ví dụ: (𝑥2); [𝑥2|𝑦2]

**Kế thừa:**[`MathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathDelimiter cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Khởi tạo MathDelimiter với phần tử được chỉ định làm đối số cơ sở duy nhất |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`arguments`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/arguments/) | Một hoặc nhiều phần tử toán học được ngăn cách bằng các ký tự delimiter |
| [`beginning_character`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Ký tự bắt đầu Delimiter chỉ định ký tự delimiter ban đầu, hoặc mở. <br/>            Các delimiter toán học là các ký tự bao quanh như dấu ngoặc tròn, ngoặc vuông và ngoặc nhọn.<br/>            Mặc định: '('. |
| [`separator_character`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/separator_character/) | Ký tự phân tách Delimiter chỉ định ký tự ngăn cách các đối số trong đối tượng delimiter. <br/>            Mặc định: '\|'. |
| [`ending_character`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/ending_character/) | Ký tự kết thúc Delimiter chỉ định ký tự delimiter cuối, hoặc đóng. <br/>            Các delimiter toán học là các ký tự bao quanh như dấu ngoặc tròn, ngoặc vuông và ngoặc nhọn.<br/>            Mặc định: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Chỉ định sự mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Khi true, các delimiter mở rộng theo chiều dọc để khớp với chiều cao của toán hạng.<br/>            Giá trị mặc định là true |
| [`delimiter_shape`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Chỉ định hình dạng của các delimiter trong đối tượng delimiter. <br/>            Khi là MathDelimiterShape.Centered, các delimiter được căn giữa trục toán học của văn bản toán học <br/>            và vẫn được điều chỉnh để vừa với toàn bộ chiều cao của nội dung.<br/>            Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/join/#str) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác để đóng khung |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/enclose/#) | Bao quanh một phần tử toán học trong dấu ngoặc |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/function/#str) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Lấy hàm đã chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Lấy hàm đã chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm đã chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm đã chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm đã chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Chỉ định căn bậc của mức độ đã cho từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/radical/#str) | Chỉ định căn bậc của mức độ đã cho từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Lấy tích phân không giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/group/#) | Đặt phần tử này vào một nhóm sử dụng ngoặc nhọn dưới cùng |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như ngoặc nhọn dưới cùng hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/accent/#char) | Đặt dấu phụ (một ký tự trên đầu phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/overbar/#) | Đặt một thanh ở phía trên của phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/underbar/#) | Đặt một thanh ở phía dưới của phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác.<br/>            Một đối tượng được đóng khung có thể (ví dụ) hoạt động như một mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            hoạt động như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`delimit(self, separator_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Phân tách các đối số bằng ký tự delimiter được chỉ định |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)