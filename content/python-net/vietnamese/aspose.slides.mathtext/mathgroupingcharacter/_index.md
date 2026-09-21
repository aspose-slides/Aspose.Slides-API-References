---
title: MathGroupingCharacter class
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter lớp

Xác định một ký tự nhóm phía trên hoặc phía dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử

**Kế thừa:**[`MathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathGroupingCharacter cung cấp các thành viên sau:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Khởi tạo một thể hiện mới của lớp MathGroupingCharacter <br/>            với ký tự nhóm mặc định U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Khởi tạo một thể hiện mới của lớp MathGroupingCharacter. |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/base/) | Đối số cơ bản |
| [`character`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/character/) | Ký tự nhóm<br/>            Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/position/) | Vị trí của ký tự nhóm.<br/>            Mặc định: Bottom |
| [`vertical_justification`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Căn chỉnh dọc của ký tự nhóm.<br/>            Xác định sự căn chỉnh của đối tượng so với đường cơ sở.<br/>            Ví dụ, khi ký tự nhóm ở trên đối tượng, <br/>            VerticalJustification giá trị Top cho biết phần trên của đối tượng nằm trên đường cơ sở;<br/>            khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở<br/>            Mặc định: Bottom cho Position=Top, và Top cho Position=Bottom |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Ghép một phần tử toán học và tạo khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Ghép một văn bản toán học và tạo khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc đơn hoặc các ký tự khác như khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và trên ở phía bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và trên ở phía bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và trên ở phía bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và trên ở phía bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Xác định căn bậc toán học của độ bậc cho trước từ đối số được chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Xác định căn bậc toán học của độ bậc cho trước từ đối số được chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Lấy tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Đặt phần tử này vào hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Đặt dấu phụ (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Đặt một thanh ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Đặt một thanh ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            hoạt động như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/mathgroupingcharacter)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)