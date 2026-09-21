---
title: MathPhantom class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathphantom/
---
## Lớp MathPhantom

Đại diện cho một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ sở trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dành chỗ. Tính hiển thị và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

**Inheritance:**[`MathPhantom`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)

Kiểu MathPhantom cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Khởi tạo một thể hiện mới của lớp [`MathPhantom`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom) <br/>            bằng cách sử dụng phần tử toán học cơ sở được chỉ định. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/base/) | Đối số cơ sở |
| [`show`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/show/) | Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [`zero_width`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/zero_width/) | Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở <br/>            có nên được coi là zero. |
| [`zero_asc`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/zero_asc/) | Lấy hoặc đặt giá trị cho biết phần tăng (chiều cao trên đường cơ sở) <br/>            của phần tử cơ sở có nên được coi là zero. |
| [`zero_desc`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/zero_desc/) | Lấy hoặc đặt giá trị cho biết phần hạ (độ sâu dưới đường cơ sở)<br/>            của phần tử cơ sở có nên được coi là zero. |
| [`transp`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/transp/) | Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt <br/>            đối với các quy tắc khoảng cách dựa trên lớp. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/join/#imathelement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/join/#str) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/divide/#str) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số được chỉ định |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số được chỉ định |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/enclose/#) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Bao quanh một phần tử toán học bằng các ký tự chỉ định như dấu ngoặc đơn hoặc các ký tự khác làm khung |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/function/#imathelement) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/function/#str) | Lấy một hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Lấy hàm chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Lấy hàm chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Lấy hàm chỉ định sử dụng thể hiện này làm đối số |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Lấy hàm chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung chỉ định |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Lấy hàm chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung chỉ định |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Tạo chỉ số dưới |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Tạo chỉ số dưới |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Tạo chỉ số trên |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Tạo chỉ số trên |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Xác định căn bậc của độ đã cho từ đối số chỉ định. |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/radical/#str) | Xác định căn bậc của độ đã cho từ đối số chỉ định. |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Lấy giới hạn trên |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Lấy giới hạn trên |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Lấy giới hạn dưới |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Lấy giới hạn dưới |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tạo một toán tử N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Tạo một toán tử N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Lấy tích phân |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Lấy tích phân không giới hạn |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Lấy tích phân |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Lấy tích phân |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/group/#) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/to_border_box/#) | Đặt phần tử này vào một hộp viền |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Đặt phần tử này vào một hộp viền |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/to_math_array/#) | Đặt vào một mảng dọc |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/accent/#char) | Đặt dấu phụ (một ký tự ở trên cùng của phần tử này) |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/overbar/#) | Đặt thanh trên phần tử này |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/underbar/#) | Đặt thanh dưới phần tử này |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/to_box/#) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) <br/>            được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác.<br/>            Một đối tượng được đóng hộp có thể (ví dụ) hoạt động như một bộ giả lập toán tử có hoặc không có điểm căn chỉnh, <br/>            hoạt động như một điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom/get_children/#) | Lấy các phần tử con |

### Xem thêm
* lớp [`MathElementBase`](/slides/python-net/vi/aspose.slides.mathtext/mathelementbase)
* lớp [`MathPhantom`](/slides/python-net/vi/aspose.slides.mathtext/mathphantom)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)