---
title: MathBorderBox class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 类

在 IMathElement 周围绘制矩形或其他形状的边框。

**继承:**[`MathBorderBox`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathBorderBox 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | 创建具有矩形边框的 MathBorderBox 元素 |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | 创建 MathBorderBox 元素 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/base/) | 基础参数 |
| [`hide_top`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/hide_top/) | 隐藏顶部边缘（默认值为 false）- 指定边框盒顶部边缘的隐藏或显示状态。 |
| [`hide_bottom`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/hide_bottom/) | 隐藏底部边缘（默认值为 false）- 指定边框盒底部边缘的隐藏或显示状态。 |
| [`hide_left`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/hide_left/) | 隐藏左侧边缘（默认值为 false）- 指定边框盒左侧边缘的隐藏或显示状态。 |
| [`hide_right`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/hide_right/) | 隐藏右侧边缘（默认值为 false）- 指定边框盒右侧边缘的隐藏或显示状态。 |
| [`strikethrough_horizontal`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | 水平删除线（默认值为 false）- 指定水平删除线的隐藏或显示状态。 |
| [`strikethrough_vertical`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | 垂直删除线（默认值为 false）- 指定垂直删除线的隐藏或显示状态。 |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | 从左下到右上删除线（默认值为 false）。<br/>            指定从左下角到右上角的对角删除线的隐藏或显示状态。 |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | 从左上到右下删除线（默认值为 false）。<br/>            指定从左上角到右下角的对角删除线的隐藏或显示状态。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/enclose/#) | 用括号包围数学元素 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | 使用指定字符（如括号或其他字符）框住数学元素 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/function/#imathelement) | 使用此实例作为函数名，接受一个参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/function/#str) | 使用此实例作为函数名，接受一个参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | 使用此实例作为参数，接受指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | 使用此实例作为参数，接受指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，接受指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，并接受指定的附加参数的函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，并接受指定的附加参数的函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | 指定给定次数的数学根号，从指定参数中取值。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/radical/#str) | 指定给定次数的数学根号，从指定参数中取值。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | 接受上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | 接受上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | 接受下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | 接受下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 接受积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | 接受积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | 接受无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 接受积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | 接受积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（例如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/to_math_array/#) | 放入垂直数组 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/accent/#char) | 设置重音符号（元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            例如，盒装对象可以充当带或不带对齐点的运算符模拟器，<br/>            充当换行点，或被分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/get_children/#) | 获取子元素 |


### 参见
* 类 [`MathBorderBox`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)