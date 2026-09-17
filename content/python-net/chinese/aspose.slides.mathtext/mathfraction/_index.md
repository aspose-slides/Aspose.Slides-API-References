---
title: MathFraction class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathfraction/
---
## MathFraction 类

指定分数对象，由分子和分母通过分数线分隔组成。分数线可以是水平的或对角的，取决于分数属性。分数对象还用于表示堆叠函数，即将一个元素放在另一个元素之上且不使用分数线。

**继承:**[`MathFraction`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathFraction 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | 使用指定的分子、分母和类型初始化 MathFraction |
| [`__init__(self, numerator, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | 使用指定的分子和分母初始化类型为 'Bar' 的 MathFraction |

## 属性

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/fraction_type/) | 分数类型<br/>            默认: Bar |
| [`numerator`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/numerator/) | 分子 |
| [`denominator`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/denominator/) | 分母 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/enclose/#) | 将数学元素括在括号中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素括起来 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/function/#imathelement) | 使用此实例作为函数名，接受参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/function/#str) | 使用此实例作为函数名，接受参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并使用指定的额外参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并使用指定的额外参数，调用指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/radical/#imathelement) | 指定给定次数的数学根，取自指定参数 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/radical/#str) | 指定给定次数的数学根，取自指定参数 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | 使用上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | 使用上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | 使用下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | 使用下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/accent/#char) | 设置重音符号（位于此元素上方的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>            用于对方程或其他数学文本的组成部分进行分组。<br/>            例如，盒状对象可以作为带或不带对齐点的运算符模拟器，<br/>            充当换行点，或被分组以不允许内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/get_children/#) | 获取子元素 |

### 另见
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathFraction`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)