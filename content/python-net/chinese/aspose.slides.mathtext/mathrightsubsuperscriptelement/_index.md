---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement 类

指定下标上标对象，该对象由基参数以及位于基参数右侧的下标和上标组成。

**继承：**[`MathRightSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathRightSubSuperscriptElement 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | 初始化 MathRightSubSuperscriptElement 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | 基参数 |
| [`subscript`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | 下标参数 |
| [`superscript`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | 上标参数 |
| [`align_scripts`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | 指定下标/上标的对齐方式。<br/>当为 true 时，下标和上标在水平方向上相互对齐。<br/>当为 false 时，它们根据基参数的形状进行字距调整。<br/>默认值为 false。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | 连接一个数学元素并形成一个数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | 连接一段数学文本并形成一个数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | 使用此分子和指定的分母创建一个分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | 使用此分子和指定的分母创建一个分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | 将数学元素括在圆括号中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | 使用指定字符（如圆括号或其他字符）将数学元素括起 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | 使用此实例作为函数名，以参数调用函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | 使用此实例作为函数名，以参数调用函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并指定额外参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并指定额外参数，调用指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | 指定从指定参数中提取给定次数的数学根 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | 指定从指定参数中提取给定次数的数学根 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取定积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 取定积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取定积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | 取定积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | 将此元素放入边框框中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框框中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | 设置重音标记（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | 在此元素顶部设置横杠 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | 在此元素底部设置横杠 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>用于对方程或其他数学文本的组成部分进行分组。<br/>例如，框对象可以充当带或不带对齐点的运算符仿真器，<br/>充当换行点，或进行分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | 获取子元素 |

### 另请参阅
* 类 [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathRightSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)