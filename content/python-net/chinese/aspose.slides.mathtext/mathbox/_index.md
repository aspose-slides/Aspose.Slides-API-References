---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathbox/
---
## MathBox 类

指定数学元素的逻辑盒装（包装）。
            例如，带盒的对象可以作为带或不带对齐点的运算符仿真器，用作换行点，或被分组以防止在其内部出现换行。例如，"==" 运算符应被盒装以防止换行。

**继承:**[`MathBox`](/slides/python-net/zh/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathBox 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/__init__/#imathelement) | 使用指定的元素作为参数初始化 MathBox |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/base/) | 基本参数 |
| [`operator_emulator`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/operator_emulator/) | 运算符仿真器。<br/>            为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。 <br/>            这意味着，例如，该字符可以作为换行点并可以与其他运算符对齐。<br/>            当一个或多个字形组合形成运算符（如 '=='）时，通常使用运算符仿真器。<br/>            默认值：false |
| [`no_break`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/no_break/) | 不换行<br/>            此属性指定对象盒的“不可换行”属性。为 true 时，盒内部不能出现换行。<br/>            对于由多个二元运算符组成的运算符仿真器，这可能很重要。 <br/>            若未指定此元素，盒内部可以换行。<br/>            默认：true |
| [`differential`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/differential/) | 微分<br/>            为 true 时，盒子充当微分（例如，积分式中的 𝑑𝑥），并获得数学微分所需的水平间距。<br/>            默认：false |
| [`alignment_point`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/alignment_point/) | 为 true 时，此运算符仿真器充当对齐点；即其他等式中指定的对齐点可以与之对齐。<br/>            默认：false |
| [`explicit_break`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/explicit_break/) | 显式换行指定在 Box 对象开始处是否存在换行，以便在盒子对象起始处换行。<br/>            指定前一行数学文本中运算符的编号，该运算符将用作当前行数学文本的对齐点。<br/>            可取值：1..255<br/>            默认：0（无显式换行） |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/join/#imathelement) | 连接数学元素并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/join/#str) | 连接数学文本并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/enclose/#) | 将数学元素用括号括起 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/enclose/#char-char) | 将数学元素用指定字符（如括号或其他字符）框起 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/function/#imathelement) | 使用此实例作为函数名，创建接受参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/function/#str) | 使用此实例作为函数名，创建接受参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，并使用指定的额外参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，并使用指定的额外参数，调用指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/radical/#imathelement) | 指定给定次数的数学根（从指定参数） |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/radical/#str) | 指定给定次数的数学根（从指定参数） |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | 设置上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | 设置上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | 设置下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | 设置下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/to_math_array/#) | 放入垂直数组 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/accent/#char) | 设置重音符号（元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/overbar/#) | 在元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/underbar/#) | 在元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/to_box/#) | 将此元素放入非可视盒（逻辑分组） <br/>            用于对等式或其他数学文本实例的组件进行分组。<br/>            例如，带盒的对象可以作为带或不带对齐点的运算符仿真器，<br/>            用作换行点，或被分组以防止在其内部出现换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/get_children/#) | 获取子元素 |


### 另请参见
* 类 [`MathBox`](/slides/python-net/zh/aspose.slides.mathtext/mathbox)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)