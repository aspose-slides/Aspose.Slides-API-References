---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathblock/
---
## MathBlock 类

指定一个数学文本实例，该实例包含在 MathParagraph 中并且单独开始于新行。  
所有数学区域，包括等式、表达式、等式或表达式的数组以及公式，都由数学块表示。

**继承:**[`MathBlock`](/slides/python-net/zh/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathBlock 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/__init__/#) | 初始化 MathBlock 类的新实例。 |
| [`__init__(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/__init__/#imathelement) | 创建一个新的数学块并将指定元素放入其中 |
| [`__init__(self, math_elements)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`count`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/count/) | 获取集合中实际包含的子数学元素的数量。<br/>            只读 **int**。 |
| [`is_read_only`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/is_read_only/) | 返回 false，因为子元素集合可以被修改。 |

获取或设置指定索引处的 IMathElement。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/__getitem__/) | 项目的零基索引 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/join/#imathelement) | 将数学元素与此数学块连接 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/join/#str) | 将数学文本与此数学块连接 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/enclose/#) | 用括号将数学元素括起来 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/enclose/#char-char) | 使用指定字符（如括号或其他字符）将此块的子元素括起来 |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | 使用指定字符（如括号或其他字符）将此块的子元素括起来<br/>            并使用分隔符字符进行分隔 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/function/#imathelement) | 使用此实例作为函数名，获取参数的函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/function/#str) | 使用此实例作为函数名，获取参数的函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，并使用指定的附加参数，获取指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，并使用指定的附加参数，获取指定函数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/radical/#imathelement) | 指定给定次数的数学根，基于指定的参数 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/radical/#str) | 指定给定次数的数学根，基于指定的参数 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | 获取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | 获取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | 获取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | 获取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | 获取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | 获取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | 获取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | 获取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/group/#) | 使用底部大括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/to_math_array/#) | 将子元素放入垂直数组 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/accent/#char) | 设置重音标记（此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/to_box/#) | 将此元素放入非可视框（逻辑分组）<br/>            用于对方程或其他数学文本实例的组件进行分组。<br/>            例如，盒装对象可以作为带或不带对齐点的运算符模拟器，<br/>            充当换行点，或进行分组以防止内部换行 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/get_children/#) | 获取子元素 |
| [`add(self, item)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/add/#imathelement) | 将数学元素添加到集合的末尾 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/clear/#) | 从集合中移除所有元素 |
| [`contains(self, item)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/contains/#imathelement) | 确定集合是否包含特定值 |
| [`copy_to(self, array, array_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | 复制到指定数组 |
| [`remove(self, item)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/remove/#imathelement) | 从集合中删除特定对象的第一次出现 |
| [`index_of(self, item)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/index_of/#imathelement) | 确定特定数学元素在集合中的索引 |
| [`insert(self, index, item)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | 在指定索引处向集合插入 MathElement |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/remove_at/#int) | 移除集合中指定索引处的元素 |
| [`join_block(self, other)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/join_block/#imathblock) | 将另一个数学块与此块连接 |
| [`delimit(self, separator_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/delimit/#char) | 使用分隔符字符（不包括括号）划分子元素 |
| [`write_as_math_ml(self, stream)`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | 将此 [`MathBlock`](/slides/python-net/zh/aspose.slides.mathtext/mathblock) 的内容保存为 MathML |

### 另请参阅
* 类 [`MathBlock`](/slides/python-net/zh/aspose.slides.mathtext/mathblock)
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)