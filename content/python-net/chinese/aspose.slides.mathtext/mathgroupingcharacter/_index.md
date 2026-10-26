---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter 类

指定表达式上方或下方的分组符号，通常用于突出元素之间的关系

**继承：**[`MathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | 初始化 MathGroupingCharacter 类的新实例<br/>使用默认分组字符 U+23DF（底部花括号） |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | 初始化 MathGroupingCharacteristic 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/base/) | 基础参数 |
| [`character`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/character/) | 分组字符<br/>默认值：U+23DF（底部花括号） |
| [`position`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/position/) | 分组字符的位置。<br/>默认：底部 |
| [`vertical_justification`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | 组字符的垂直对齐方式。<br/>指定对象相对于基线的对齐方式。<br/>例如，当组字符位于对象上方时，<br/>VerticalJustification 为 Top 表示对象的顶部位于基线上；<br/>当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上<br/>默认：Position=Top 时为 Bottom，Position=Bottom 时为 Top |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | 将数学元素连接并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | 将数学文本连接并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | 使用此分子和指定分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | 使用此分子和指定分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | 使用此分子和指定分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | 使用此分子和指定分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | 用括号将数学元素括起来 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | 使用指定字符（如括号或其他字符）将数学元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | 使用此实例作为函数名，对参数取函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | 使用此实例作为函数名，对参数取函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，取指定函数并添加指定的额外参数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，取指定函数并添加指定的额外参数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | 指定给定次数的数学根号，来自指定参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | 指定给定次数的数学根号，来自指定参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | 取没有上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/group/#) | 使用底部花括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部花括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | 放入垂直阵列 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | 设置重音符号（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | 在此元素顶部设置一条横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | 在此元素底部设置一条横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>用于对方程或其他数学文本的组件进行分组。<br/>盒装对象可以（例如）作为带或不带对齐点的运算符模拟器，<br/>作为换行点，或被分组以防止内部换行。 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | 获取子元素 |

### 另请参阅
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)