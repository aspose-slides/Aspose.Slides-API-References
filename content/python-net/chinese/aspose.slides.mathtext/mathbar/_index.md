---
title: MathBar class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathbar/
---
## MathBar 类

指定条形函数，由基础参数和上横线或下横线组成

**继承:**[`MathBar`](/slides/python-net/zh/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathBar 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/__init__/#imathelement) | 使用上横线（顶部位置）初始化 MathBar |
| [`__init__(self, element, position)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | 使用指定位置初始化 MathBar |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/base/) | 基础参数 |
| [`position`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/position/) | 条线的位置。<br/>            默认：顶部 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/enclose/#) | 用括号括住数学元素 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素括起来作为框架 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/function/#imathelement) | 使用此实例作为函数名获取参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/function/#str) | 使用此实例作为函数名获取参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数获取指定函数并添加额外参数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数获取指定函数并添加额外参数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/radical/#imathelement) | 指定给定次数的数学根，基于指定参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/radical/#str) | 指定给定次数的数学根，基于指定参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | 获取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | 获取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | 获取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | 获取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | 获取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | 获取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | 获取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/accent/#char) | 设置重音符号（此元素上方的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            例如，盒装对象可以作为带或不带对齐点的运算符仿真器，<br/>            作为换行点，或进行分组以阻止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/get_children/#) | 获取子元素 |

### 另请参阅
* 类 [`MathBar`](/slides/python-net/zh/aspose.slides.mathtext/mathbar)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)