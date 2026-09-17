---
title: MathLeftSubSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement 类

指定下标-上标对象，该对象由基底以及放置在基底左侧的下标和上标组成。

**继承：**[`MathLeftSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement) → [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathLeftSubSuperscriptElement 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | 初始化 MathLeftSubSuperscriptElement 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/base/) | 基底参数 |
| [`subscript`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/subscript/) | 下标 |
| [`superscript`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/superscript/) | 上标 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/join/#imathelement) | 将数学元素连接并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/join/#str) | 将数学文本连接并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/enclose/#) | 用括号括住数学元素 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素括起来 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/function/#imathelement) | 使用此实例作为函数名，对参数进行函数调用 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/function/#str) | 使用此实例作为函数名，对参数进行函数调用 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/as_argument_of_function/#imathelement) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/as_argument_of_function/#str) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并使用指定的附加参数调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并使用指定的附加参数调用指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/radical/#imathelement) | 指定给定次数的数学根号，来自指定的参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/radical/#str) | 指定给定次数的数学根号，来自指定的参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_upper_limit/#imathelement) | 使用上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_upper_limit/#str) | 使用上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_lower_limit/#imathelement) | 使用下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/set_lower_limit/#str) | 使用下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 计算积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 计算积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/integral/#mathintegraltypes) | 计算无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 计算积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/integral/#mathintegraltypes-str-str) | 计算积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/#) | 使用底部大括号将此元素放入分组 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入分组 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/to_border_box/#) | 将此元素放入边框盒 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/to_math_array/#) | 放入垂直数组 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/to_box/#) | 将此元素放置在非可视框（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            盒状对象（例如）可以作为带或不带对齐点的运算符模拟器，<br/>            充当换行点，或被分组以禁止其中换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_children/#) | 获取子元素 |

### 另见
* 类 [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathLeftSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)