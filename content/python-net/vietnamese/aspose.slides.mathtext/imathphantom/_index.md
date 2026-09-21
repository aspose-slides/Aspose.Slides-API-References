---
title: IMathPhantom class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/imathphantom/
---
## lớp IMathPhantom

Biểu diễn một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ bản trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dành không gian. Tính hiển thị và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

Kiểu IMathPhantom cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`base`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/base/) | Đối số cơ bản |
| [`show`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/show/) | Lấy hoặc đặt giá trị cho biết phần tử cơ bản có được hiển thị hay không. |
| [`zero_width`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/zero_width/) | Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ bản <br/>            có nên được coi là zero. |
| [`zero_asc`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/zero_asc/) | Lấy hoặc đặt giá trị cho biết phần lên (chiều cao phía trên đường cơ sở) <br/>            của phần tử cơ bản có nên được coi là zero. |
| [`zero_desc`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/zero_desc/) | Lấy hoặc đặt giá trị cho biết phần xuống (độ sâu phía dưới đường cơ sở)<br/>            của phần tử cơ bản có nên được coi là zero. |
| [`transp`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/transp/) | Lấy hoặc đặt giá trị cho biết đối tượng ảo là trong suốt <br/>            đối với các quy tắc khoảng cách dựa trên lớp. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/vi/aspose.slides.mathtext/imathphantom/to_box/#) |  |

### Xem thêm
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)