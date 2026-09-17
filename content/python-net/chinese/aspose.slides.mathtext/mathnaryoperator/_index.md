---
title: MathNaryOperator class
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator 类

指定一个 N 元数学对象，例如求和和积分。            
它由一个运算符、一个基数（或操作数）以及可选的上限和下限组成。            
N 元运算符的示例包括：求和、并集、交集、积分

**继承:**[`MathNaryOperator`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathNaryOperator 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | 初始化 MathNaryOperator 类的新实例。 |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | 初始化 MathNaryOperator 类的新实例。 |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | 初始化 MathNaryOperator 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/base/) | 基数参数 |
| [`subscript`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/subscript/) | 指定下标参数，例如在积分的情况下，设置下限 |
| [`superscript`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/superscript/) | 指定上标参数，例如在积分的情况下，设置上限 |
| [`operator`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/operator/) | N 元运算符字符<br/>            例如：'∑', '∫' |
| [`limit_location`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/limit_location/) | 限制的位置（下标和上标） |
| [`grow_to_match_operand_height`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | 运算符字符垂直伸展以匹配其操作数的高度 |
| [`hide_subscript`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | 隐藏下标 |
| [`hide_superscript`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | 隐藏上标 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | 将数学元素连接并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/join/#str) | 将数学文本连接并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/enclose/#) | 将数学元素用括号括起来 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素框起来 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | 使用此实例作为函数名，获取带参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/function/#str) | 使用此实例作为函数名，获取带参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，并使用指定的附加参数获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，并使用指定的附加参数获取指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | 从指定参数计算指定次数的数学根。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/radical/#str) | 从指定参数计算指定次数的数学根。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | 获取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | 获取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | 获取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | 获取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | 获取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | 获取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | 获取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            例如，盒装对象可以用作具有或不具有对齐点的运算符仿真器，<br/>            充当换行点，或进行分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/get_children/#) | 获取子元素 |

### 另请参见
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathNaryOperator`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)