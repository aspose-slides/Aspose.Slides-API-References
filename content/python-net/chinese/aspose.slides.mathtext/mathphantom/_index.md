---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathphantom/
---
## MathPhantom 类

表示一个幻影数学对象 (<m:phant>)，它会影响其子元素的布局，但不一定显示它。幻影可以隐藏其基表达式，同时保留其宽度、高度或深度，以对齐公式或预留空间。可通过属性如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 来控制可见性和几何行为。

**继承:**[`MathPhantom`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathPhantom 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | 初始化 [`MathPhantom`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom) 类的新实例 <br/> 使用指定的基数学元素。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/base/) | 基参数 |
| [`show`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/show/) | 获取或设置一个值，指示基元素是否显示。 |
| [`zero_width`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/zero_width/) | 获取或设置一个值，指示基元素的宽度 <br/> 是否应视为零。 |
| [`zero_asc`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/zero_asc/) | 获取或设置一个值，指示基元素的上升（基线以上的高度） <br/> 是否应视为零。 |
| [`zero_desc`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/zero_desc/) | 获取或设置一个值，指示基元素的下降（基线以下的深度）<br/> 是否应视为零。 |
| [`transp`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/transp/) | 获取或设置一个值，指示幻影在基于类的间距规则下是否透明 <br/>。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/join/#imathelement) | 连接一个数学元素并形成一个数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/join/#str) | 连接一段数学文本并形成一个数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/enclose/#) | 将数学元素用括号括起 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素框起来 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/function/#imathelement) | 使用此实例作为函数名，对一个参数采用函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/function/#str) | 使用此实例作为函数名，对一个参数采用函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，调用指定函数并附加指定的额外参数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，调用指定函数并附加指定的额外参数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/radical/#imathelement) | 指定给定次数的数学根，使用指定的参数 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/radical/#str) | 指定给定次数的数学根，使用指定的参数 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/accent/#char) | 设置重音标记（元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/overbar/#) | 在此元素顶部设置一条横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/underbar/#) | 在此元素底部设置一条横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/to_box/#) | 将此元素放入非可视框（逻辑分组） <br/> 用于对方程或其他数学文本的组件进行分组。<br/> 该盒装对象可以（例如）作为带或不带对齐点的运算符仿真器，<br/> 作为换行点，或进行分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/get_children/#) | 获取子元素 |


### 另见
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathPhantom`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)