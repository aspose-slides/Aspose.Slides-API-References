---
title: MathFunction class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathfunction/
---
## MathFunction 类

指定一个参数的函数。

**Inheritance:**[`MathFunction`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathFunction 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | 初始化 MathFunction 类的新实例。 |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | 初始化 MathFunction 类的新实例。 |

## 属性

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/name/) | 函数名<br/>            例如，函数名有 sin 和 cos |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/base/) | 函数参数 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/enclose/#) | 将数学元素包裹在括号中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素包裹起来 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/function/#imathelement) | 使用此实例作为函数名获取一个参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/function/#str) | 使用此实例作为函数名获取一个参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并指定额外参数获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并指定额外参数获取指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/radical/#imathelement) | 指定给定次数的数学根号，以指定的参数为底。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/radical/#str) | 指定给定次数的数学根号，以指定的参数为底。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/group/#) | 使用底部花括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（例如底部花括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/to_math_array/#) | 放入垂直阵列 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>            用于对方程或其他数学文本实例的组成部分进行分组。<br/>            盒式对象可以（例如）用作带或不带对齐点的运算符仿真器，<br/>            用作换行点，或进行分组以防止其中出现换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/get_children/#) | 获取子元素 |


### 另见
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathFunction`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)