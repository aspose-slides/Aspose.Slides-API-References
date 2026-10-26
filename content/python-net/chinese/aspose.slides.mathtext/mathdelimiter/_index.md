---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter 类

指定分隔符对象，由开闭字符（如括号、花括号、方括号和竖线）组成，并包含一个或多个数学元素，这些元素通过指定字符分隔。示例：(𝑥2); [𝑥2|𝑦2]

**继承：**[`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathDelimiter 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | 使用指定的元素作为单一基础参数初始化 MathDelimiter |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`arguments`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/arguments/) | 一个或多个由分隔符字符分隔的数学元素 |
| [`beginning_character`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character 指定起始或打开的分隔符字符。<br/>            数学分隔符是诸如括号、方括号和花括号等闭合字符。<br/>            默认值：'('。 |
| [`separator_character`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character 指定在分隔符对象中分隔参数的字符。<br/>            默认值：'\|'. |
| [`ending_character`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character 指定结束或关闭的分隔符字符。<br/>            数学分隔符是诸如括号、方括号和花括号等闭合字符。<br/>            默认值：')'. |
| [`grow_to_match_operand_height`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            当为 true 时，分隔符会垂直增长以匹配其操作数的高度。<br/>            默认值为 true |
| [`delimiter_shape`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Specifies the shape of delimiters in the delimiter object. <br/>            当为 MathDelimiterShape.Centered 时，分隔符在数学文本的数学轴上居中，并且仍会调整以适应其内容的整体高度。<br/>            当为 MathDelimiterShape.Match 时，其高度和形状会被修改以完全匹配其内容。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 连接一个数学元素并形成一个数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/join/#str) | 连接一段数学文本并形成一个数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素包围起来作为框架 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/enclose/#) | 在括号中包围数学元素 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | 使用此实例作为函数名，对参数进行函数调用 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/function/#str) | 使用此实例作为函数名，对参数进行函数调用 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数并传入指定的附加参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数并传入指定的附加参数，调用指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 指定给定次数的数学根，从指定的参数计算。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/radical/#str) | 指定给定次数的数学根，从指定的参数计算。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（例如底部大括号或其他字符）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 放入垂直数组中 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/accent/#char) | 设置重音标记（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>            用于对方程或其他数学文本实例的组成部分进行分组。<br/>            盒状对象可以（例如）充当带或不带对齐点的运算符仿真器，<br/>            充当换行点，或被分组以防止其内部出现换行。 |
| [`delimit(self, separator_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 使用指定的分隔符字符界定参数 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/get_children/#) | 获取子元素 |

### 另请参见
* 类 [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)