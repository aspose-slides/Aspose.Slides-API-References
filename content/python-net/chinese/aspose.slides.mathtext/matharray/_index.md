---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/matharray/
---
## MathArray 类

指定一个垂直的方程或任何数学对象的数组

**继承:**[`MathArray`](/slides/python-net/zh/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathArray 类型公开以下成员:

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/__init__/#imathelement) | 创建一个数学数组并将指定的元素放入其中 |
| [`__init__(self, elements)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`arguments`](/slides/python-net/zh/aspose.slides.mathtext/matharray/arguments/) | 数组的项集合 |
| [`base_justification`](/slides/python-net/zh/aspose.slides.mathtext/matharray/base_justification/) | 指定数组相对于周围文本的对齐方式<br/>            数组外部的文本可以与数组对象的底部、顶部或中心对齐。<br/>            默认值：Center |
| [`maximum_distribution`](/slides/python-net/zh/aspose.slides.mathtext/matharray/maximum_distribution/) | 最大分布<br/>            当为 true 时，数组会被间隔至包含元素（页面、列、单元格等）的最大宽度。 |
| [`object_distribution`](/slides/python-net/zh/aspose.slides.mathtext/matharray/object_distribution/) | 对象分布<br/>            当为 true 时，数组的内容会被间隔至数组对象的最大宽度。 |
| [`row_spacing_rule`](/slides/python-net/zh/aspose.slides.mathtext/matharray/row_spacing_rule/) | 数组元素之间的垂直间距类型<br/>            默认：SingleLineGap |
| [`row_spacing`](/slides/python-net/zh/aspose.slides.mathtext/matharray/row_spacing/) | 数组行之间的间距<br/>            仅在 RowSpacingRule 设置为 3 Exactly 时使用，此时度量单位为点 <br/>            或者在 Multiple 时度量单位为半行。<br/>            默认：0 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/enclose/#) | 将数学元素括在括号中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/enclose/#char-char) | 将数学元素用指定字符（如括号或其他字符）括起来作为框架 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/function/#imathelement) | 使用此实例作为函数名获取参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/function/#str) | 使用此实例作为函数名获取参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数获取指定函数，并使用指定的附加参数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数获取指定函数，并使用指定的附加参数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/radical/#imathelement) | 指定给定次数的数学根，使用指定的参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/radical/#str) | 指定给定次数的数学根，使用指定的参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | 获取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_upper_limit/#str) | 获取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | 获取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/set_lower_limit/#str) | 获取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | 获取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | 获取无界限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | 获取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/to_box/#) | 将此元素放入非可视框（逻辑分组） <br/>            用于将方程或其他数学文本实例的组件分组。<br/>            盒状对象可以（例如）作为带或不带对齐点的运算符仿真器，<br/>            作为换行点，或进行分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/matharray/get_children/#) | 获取子元素 |


### 另请参见
* 类 [`MathArray`](/slides/python-net/zh/aspose.slides.mathtext/matharray)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)