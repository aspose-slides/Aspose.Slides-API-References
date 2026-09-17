---
title: IMathNaryOperator class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.mathtext/imathnaryoperator/
---
## IMathNaryOperator 类

指定一个 N 进制数学对象，例如 Summation 和 Integral。  
它由一个运算符、一个基（或操作数）以及可选的上限和下限组成。  
N 进制运算符的例子有：Summation、Union、Intersection、Integral

IMathNaryOperator 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/base/) | 基参数 |
| [`subscript`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/subscript/) | 指定下标参数，例如在积分的情况下设置下限 |
| [`superscript`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/superscript/) | 指定上标参数，例如在积分的情况下设置上限 |
| [`operator`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/operator/) |  |
| [`limit_location`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/limit_location/) |  |
| [`grow_to_match_operand_height`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/grow_to_match_operand_height/) |  |
| [`hide_subscript`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/hide_subscript/) |  |
| [`hide_superscript`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/hide_superscript/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/to_box/#) |  |

### 另见
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)