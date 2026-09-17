---
title: MathSubscriptElement class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement 类

指定下标对象，该对象由一个基底和一个放置在右下方的缩小尺寸下标组成。

**继承:**[`MathSubscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathSubscriptElement 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | 初始化 MathSubscriptElement 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/base/) | 基参数 |
| [`subscript`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/subscript/) | 下标 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | 将数学元素用括号包围 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | 使用此实例作为函数名，对参数取函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/function/#str) | 使用此实例作为函数名，对参数取函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，并使用指定的附加参数取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，并使用指定的附加参数取指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | 指定给定次数的数学根，来自指定的参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | 指定给定次数的数学根，来自指定的参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | 设置重音标记（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>            用于对方程或其他数学文本的组成部分进行分组。<br/>            例如，盒装对象可以作为带或不带对齐点的运算符仿真器，<br/>            也可以作为换行点，或进行分组以避免内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | 获取子元素 |

### 另请参见
* 类 [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathSubscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)