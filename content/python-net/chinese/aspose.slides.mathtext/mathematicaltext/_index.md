---
title: MathematicalText class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText 类

数学文本

**继承:**[`MathematicalText`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathematicalText 类型公开以下成员：

## 构造函数

| 构造函数 | 说明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/__init__/#) | 默认构造函数（创建 String.Empty 值） |
| [`__init__(self, math_symbol)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/__init__/#char) | 使用单个符号创建 MathText |
| [`__init__(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/__init__/#str) | 从文本创建 MathematicalText |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | 从文本和格式设置创建 MathematicalText |

## 属性

| 属性 | 说明 |
| :- | :- |
| [`value`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/value/) | 文本值 |
| [`format`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/format/) | 文本格式属性 |

## 方法

| 方法 | 说明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | 使用此分子和指定分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/divide/#str) | 使用此分子和指定分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | 使用此分子和指定分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | 使用此分子和指定分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/enclose/#) | 用括号将数学元素括起来 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | 用指定字符（如括号或其他字符）将数学元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | 使用此实例作为函数名，获取一个参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/function/#str) | 使用此实例作为函数名，获取一个参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并指定额外参数，获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并指定额外参数，获取指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | 指定给定次数的数学根，基于指定参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/radical/#str) | 指定给定次数的数学根，基于指定参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | 获取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | 获取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | 获取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | 获取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | 获取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | 获取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | 获取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/group/#) | 使用底部花括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部花括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | 放入垂直阵列 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            例如，盒装对象可以作为带或不带对齐点的运算符仿真器，<br/>            充当换行点，或进行分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### 另请参阅
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathematicalText`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)