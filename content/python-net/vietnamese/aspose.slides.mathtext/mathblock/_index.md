---
title: MathBlock class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathblock/
---
## lớp MathBlock

Xác định một thể hiện của văn bản toán học nằm trong một MathParagraph và bắt đầu trên một dòng riêng. Tất cả các vùng toán học, bao gồm phương trình, biểu thức, mảng các phương trình hoặc biểu thức và công thức đều được biểu diễn bằng khối toán học.

**Kế thừa:**[`MathBlock`](/slides/python-net/vi/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathBlock cung cấp các thành viên sau:

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/__init__/#) | Khởi tạo một thể hiện mới của lớp MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Tạo một khối toán học mới và đặt phần tử được chỉ định vào trong đó |
| [`__init__(self, math_elements)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`count`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/count/) | Lấy số lượng phần tử toán học con thực sự chứa trong bộ sưu tập.<br/>            Chỉ đọc **int**. |
| [`is_read_only`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/is_read_only/) | Trả về false vì bộ sưu tập phần tử con có thể được chỉnh sửa. |

Lấy hoặc đặt IMathElement tại chỉ mục được chỉ định.

## Trình truy cập

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/__getitem__/) | Chỉ mục bắt đầu từ 0 của mục |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/join/#imathelement) | Nối một phần tử toán học với khối toán học này |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/join/#str) | Nối một văn bản toán học với khối toán học này |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/enclose/#char-char) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung<br/>            và phân tách bằng một ký tự ngăn cách |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/function/#imathelement) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/function/#str) | Nhận một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Nhận một hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Nhận một hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Nhận một hàm được chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nhận một hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nhận một hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/radical/#imathelement) | Xác định căn bậc n của đối số đã cho. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/radical/#str) | Xác định căn bậc n của đối số đã cho. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Nhận giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Nhận giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Nhận giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Nhận giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Nhận tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Nhận tích phân không có giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nhận tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Nhận tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/group/#) | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm sử dụng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/to_math_array/#) | Đặt các phần tử con vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/accent/#char) | Đặt dấu phụ (một ký tự ở trên phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/overbar/#) | Đặt một gạch ngang ở trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/underbar/#) | Đặt một gạch ngang ở dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các thể hiện toán học khác.<br/>            Một đối tượng được đóng khung có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, <br/>            phục vụ như một điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/get_children/#) | Lấy các phần tử con |
| [`add(self, item)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/add/#imathelement) | Thêm một phần tử toán học vào cuối bộ sưu tập. |
| [`clear(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/clear/#) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [`contains(self, item)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/contains/#imathelement) | Xác định bộ sưu tập có chứa một giá trị cụ thể hay không. |
| [`copy_to(self, array, array_index)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Sao chép vào mảng đã chỉ định. |
| [`remove(self, item)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/remove/#imathelement) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [`index_of(self, item)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Xác định chỉ mục của một phần tử toán học cụ thể trong bộ sưu tập. |
| [`insert(self, index, item)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Chèn một MathElement vào bộ sưu tập tại chỉ mục được chỉ định. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/remove_at/#int) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [`join_block(self, other)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Nối một khối toán học khác với khối này |
| [`delimit(self, separator_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/delimit/#char) | Phân cách các phần tử con bằng ký tự ngăn cách (không có ngoặc) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/vi/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Lưu nội dung của [`MathBlock`](/slides/python-net/vi/aspose.slides.mathtext/mathblock) này dưới dạng MathML |

### Xem thêm
* lớp [`MathBlock`](/slides/python-net/vi/aspose.slides.mathtext/mathblock)
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)