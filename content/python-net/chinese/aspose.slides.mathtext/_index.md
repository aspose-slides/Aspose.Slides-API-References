---
title: aspose.slides.mathtext
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/
---
包含用于在 Microsoft PowerPoint 演示文稿中处理数学文本的类。

## 类

| 类 | 描述 |
| :- | :- |
| [`BaseScript`](/slides/python-net/zh/aspose.slides.mathtext/basescript/) | 数学脚本 |
| [`IMathAccent`](/slides/python-net/zh/aspose.slides.mathtext/imathaccent/) | 指定重音功能，由基底和组合变音标组成<br/> 示例：𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathaccentfactory/) | 允许创建数学重音 |
| [`IMathArray`](/slides/python-net/zh/aspose.slides.mathtext/imatharray/) | 指定方程或任何数学对象的垂直数组 |
| [`IMathArrayFactory`](/slides/python-net/zh/aspose.slides.mathtext/imatharrayfactory/) | 允许创建数学数组 |
| [`IMathBar`](/slides/python-net/zh/aspose.slides.mathtext/imathbar/) | 指定条形函数，由基参数和上横线或下横线组成 |
| [`IMathBarFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathbarfactory/) | 允许创建数学条形 |
| [`IMathBlock`](/slides/python-net/zh/aspose.slides.mathtext/imathblock/) | 指定一个包含在 MathParagraph 中并独立成行的数学文本实例。<br/> 所有数学区域，包括方程式、表达式、方程或表达式数组以及公式，都由 math block 表示。 |
| [`IMathBlockCollection`](/slides/python-net/zh/aspose.slides.mathtext/imathblockcollection/) | math block (IMathBlock) 的集合 |
| [`IMathBlockFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathblockfactory/) | 允许创建 math block |
| [`IMathBorderBox`](/slides/python-net/zh/aspose.slides.mathtext/imathborderbox/) | 在 IMathElement 周围绘制矩形或其他边框。 |
| [`IMathBorderBoxFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathborderboxfactory/) | 允许创建 math border box |
| [`IMathBox`](/slides/python-net/zh/aspose.slides.mathtext/imathbox/) | 指定数学元素的逻辑盒装（包装）。<br/> 例如，盒装对象可以作为带或不带对齐点的运算符模拟器，<br/> 充当换行点，或被分组以防止内部换行。<br/> 例如，"==" 运算符应进行盒装以防止换行。 |
| [`IMathBoxFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathboxfactory/) | 允许创建 math box |
| [`IMathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiter/) | 指定分隔符对象，由开启和关闭字符（例如括号、<br/> 大括号、方括号和竖线）以及内部的一个或多个数学元素组成，这些元素由指定字符分隔。<br/> 示例：(𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathdelimiterfactory/) | 允许创建 math delimiter |
| [`IMathElement`](/slides/python-net/zh/aspose.slides.mathtext/imathelement/) | 任何数学元素的基础接口：<br/> 分数、数学文本、函数、包含多个元素的表达式等 |
| [`IMathElementCollection`](/slides/python-net/zh/aspose.slides.mathtext/imathelementcollection/) | 表示数学元素 (MathElement) 的集合。 |
| [`IMathFraction`](/slides/python-net/zh/aspose.slides.mathtext/imathfraction/) | 指定分数对象，由分子和分母通过分数线分隔。<br/> 分数线可水平或对角线，取决于分数属性。<br/> 该分数对象也用于表示堆叠函数，将一个元素置于另一个之上，且没有分数线。 |
| [`IMathFractionFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathfractionfactory/) | 允许创建 math fraction |
| [`IMathFunction`](/slides/python-net/zh/aspose.slides.mathtext/imathfunction/) | 指定参数函数。 |
| [`IMathFunctionFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathfunctionfactory/) | 允许创建 math function |
| [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter/) | 指定放置在表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [`IMathGroupingCharacterFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacterfactory/) | 允许创建 math grouping character |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | 指定上下标对象，由基底<br/> 和放在基底左侧的下标和上标组成。 |
| [`IMathLimit`](/slides/python-net/zh/aspose.slides.mathtext/imathlimit/) | 指定极限对象，由基线上的文本以及其上方或下方的缩小文本组成。 |
| [`IMathLimitFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathlimitfactory/) | 允许创建 IMathLimit |
| [`IMathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/) | 指定矩阵对象，由子元素排列在一个或多个行列中。<br/> 需要注意矩阵本身没有内置分隔符。<br/> 若要在括号中放置矩阵，应使用分隔符对象 (IMathDelimiter)。<br/> 可使用空参数在矩阵中创建间隙。 |
| [`IMathMatrixFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrixfactory/) | 允许创建 math matrix |
| [`IMathNaryOperator`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperator/) | 指定 N 元数学对象，如求和和积分。<br/> 它由运算符、基底（或操作数）以及可选的上、下限组成。<br/> N 元运算符示例：求和、并集、交集、积分 |
| [`IMathNaryOperatorFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperatorfactory/) | 允许创建 IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/zh/aspose.slides.mathtext/imathnaryoperatorproperties/) | 指定 IMathNaryOperator 的属性 |
| [`IMathParagraph`](/slides/python-net/zh/aspose.slides.mathtext/imathparagraph/) | 数学段落，作为数学块 (IMathBlock) 的容器 |
| [`IMathParagraphFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathparagraphfactory/) | 允许创建 math paragraph |
| [`IMathPhantom`](/slides/python-net/zh/aspose.slides.mathtext/imathphantom/) | 表示 phantom math 对象 (<m:phant>)，它影响子元素的布局<br/> 而不一定显示出来。phantom 可以隐藏其基底表达式，同时保留其宽度、高度或深度，以对齐公式或预留空间。<br/> 可通过 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 等属性控制可见性和几何行为。 |
| [`IMathPortion`](/slides/python-net/zh/aspose.slides.mathtext/imathportion/) | 表示内部包含数学上下文的部分。 |
| [`IMathRadical`](/slides/python-net/zh/aspose.slides.mathtext/imathradical/) | 指定根函数，由基底和可选的指数组成。<br/> 根对象示例为 √𝑥。 |
| [`IMathRadicalFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathradicalfactory/) | 允许创建 math radical |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | 指定上下标对象，由基底<br/> 和放在基底右侧的下标和上标组成。 |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | 允许创建 IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/imathsubscriptelement/) | 指定下标对象，由基底<br/> 和放置在右下方的缩小下标组成。 |
| [`IMathSubscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathsubscriptelementfactory/) | 允许创建 IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/imathsuperscriptelement/) | 指定上标对象，由基底<br/> 和放置在右上方的缩小上标组成。 |
| [`IMathSuperscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathsuperscriptelementfactory/) | 允许创建 IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/zh/aspose.slides.mathtext/imathematicaltext/) | 数学文本 |
| [`IMathematicalTextFactory`](/slides/python-net/zh/aspose.slides.mathtext/imathematicaltextfactory/) | 允许创建 MathematicalText 元素 |
| [`MathAccent`](/slides/python-net/zh/aspose.slides.mathtext/mathaccent/) | 指定重音功能，由基底和组合变音标组成<br/> 示例：𝑎́ |
| [`MathAccentFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathaccentfactory/) | 允许创建数学重音 |
| [`MathArray`](/slides/python-net/zh/aspose.slides.mathtext/matharray/) | 指定方程或任何数学对象的垂直数组 |
| [`MathArrayFactory`](/slides/python-net/zh/aspose.slides.mathtext/matharrayfactory/) | 允许创建数学数组 |
| [`MathBar`](/slides/python-net/zh/aspose.slides.mathtext/mathbar/) | 指定条形函数，由基参数和上横线或下横线组成 |
| [`MathBarFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathbarfactory/) | 允许创建数学条形 |
| [`MathBlock`](/slides/python-net/zh/aspose.slides.mathtext/mathblock/) | 指定一个包含在 MathParagraph 中并独立成行的数学文本实例。<br/> 所有数学区域，包括方程式、表达式、方程或表达式数组以及公式，都由 math block 表示。 |
| [`MathBlockFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathblockfactory/) | 允许创建 math block |
| [`MathBorderBox`](/slides/python-net/zh/aspose.slides.mathtext/mathborderbox/) | 在 IMathElement 周围绘制矩形或其他边框。 |
| [`MathBorderBoxFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathborderboxfactory/) | 允许创建 math border box |
| [`MathBox`](/slides/python-net/zh/aspose.slides.mathtext/mathbox/) | 指定数学元素的逻辑盒装（包装）。<br/> 例如，盒装对象可以作为带或不带对齐点的运算符模拟器，<br/> 充当换行点，或被分组以防止内部换行。<br/> 例如，"==" 运算符应进行盒装以防止换行。 |
| [`MathBoxFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathboxfactory/) | 允许创建 math box |
| [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter/) | 指定分隔符对象，由开启和关闭字符（例如括号、<br/> 大括号、方括号和竖线）以及内部的一个或多个数学元素组成，这些元素由指定字符分隔。<br/> 示例：(𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiterfactory/) | 允许创建 math delimiter |
| [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase/) | IMathElement 基类，提供所有派生类通用的部分方法实现<br/> 仅供内部使用。派生类必须是 IMathElement。 |
| [`MathFraction`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction/) | 指定分数对象，由分子和分母通过分数线分隔。<br/> 分数线可水平或对角线，取决于分数属性。<br/> 该分数对象也用于表示堆叠函数，将一个元素置于另一个之上，且没有分数线。 |
| [`MathFractionFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathfractionfactory/) | 允许创建 math fraction |
| [`MathFunction`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction/) | 指定参数函数。 |
| [`MathFunctionFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathfunctionfactory/) | 允许创建 math function |
| [`MathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacter/) | 指定放置在表达式上方或下方的分组符号，通常用于突出元素之间的关系 |
| [`MathGroupingCharacterFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathgroupingcharacterfactory/) | 允许创建 math grouping character |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | 指定上下标对象，由基底<br/> 和放在基底左侧的下标和上标组成。 |
| [`MathLimit`](/slides/python-net/zh/aspose.slides.mathtext/mathlimit/) | 指定极限对象，由基线上的文本以及其上方或下方的缩小文本组成。 |
| [`MathLimitFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathlimitfactory/) | 允许创建 IMathLimit |
| [`MathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/) | 指定矩阵对象，由子元素排列在一个或多个行列中。<br/> 需要注意矩阵本身没有内置分隔符。<br/> 若要在括号中放置矩阵，应使用分隔符对象 (IMathDelimiter)。<br/> 可使用空参数在矩阵中创建间隙。 |
| [`MathMatrixFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrixfactory/) | 允许创建 math matrix |
| [`MathNaryOperator`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperator/) | 指定 N 元数学对象，如求和和积分。<br/> 它由运算符、基底（或操作数）以及可选的上、下限组成。<br/> N 元运算符示例：求和、并集、交集、积分 |
| [`MathNaryOperatorFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperatorfactory/) | 允许创建 IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraph/) | 数学段落，作为数学块 (IMathBlock) 的容器 |
| [`MathParagraphFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathparagraphfactory/) | 允许创建 math paragraph |
| [`MathPhantom`](/slides/python-net/zh/aspose.slides.mathtext/mathphantom/) | 表示 phantom math 对象 (<m:phant>)，它影响子元素的布局<br/> 而不一定显示出来。phantom 可以隐藏其基底表达式，同时保留其宽度、高度或深度，以对齐公式或预留空间。<br/> 可通过 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 等属性控制可见性和几何行为。 |
| [`MathPortion`](/slides/python-net/zh/aspose.slides.mathtext/mathportion/) | 表示内部包含数学上下文的部分。 |
| [`MathRadical`](/slides/python-net/zh/aspose.slides.mathtext/mathradical/) | 指定根函数，由基底和可选的指数组成。<br/> 根对象示例为 √𝑥。 |
| [`MathRadicalFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathradicalfactory/) | 允许创建 math radical |
| [`MathRightSubSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | 指定上下标对象，由基底<br/> 和放在基底右侧的下标和上标组成。 |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | 允许创建 IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelement/) | 指定下标对象，由基底<br/> 和放置在右下方的缩小下标组成。 |
| [`MathSubscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathsubscriptelementfactory/) | 允许创建 IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/zh/aspose.slides.mathtext/mathsuperscriptelement/) | 指定上标对象，由基底<br/> 和放置在右上方的缩小上标组成。 |
| [`MathSuperscriptElementFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathsuperscriptelementfactory/) | 允许创建 IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltext/) | 数学文本 |
| [`MathematicalTextFactory`](/slides/python-net/zh/aspose.slides.mathtext/mathematicaltextfactory/) | 允许创建 MathematicalText 元素 |

## 枚举

| 枚举 | 描述 |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimitershape/) | 分隔符相对于操作数内容的位置和大小 |
| [`MathFractionTypes`](/slides/python-net/zh/aspose.slides.mathtext/mathfractiontypes/) | 分数类型 |
| [`MathFunctionsOfOneArgument`](/slides/python-net/zh/aspose.slides.mathtext/mathfunctionsofoneargument/) | 单参数常用数学函数 |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/zh/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | 双参数常用数学函数 |
| [`MathHorizontalAlignment`](/slides/python-net/zh/aspose.slides.mathtext/mathhorizontalalignment/) | 水平对齐 |
| [`MathIntegralTypes`](/slides/python-net/zh/aspose.slides.mathtext/mathintegraltypes/) | 数学积分类型 |
| [`MathJustification`](/slides/python-net/zh/aspose.slides.mathtext/mathjustification/) | 指定数学段落的对齐方式（同一段落内相邻的数学文本实例系列） |
| [`MathLimitLocations`](/slides/python-net/zh/aspose.slides.mathtext/mathlimitlocations/) | n 元运算符中上下标的位置 |
| [`MathNaryOperatorTypes`](/slides/python-net/zh/aspose.slides.mathtext/mathnaryoperatortypes/) | Nary 操作符 IMathNaryOperator 类型（不包括积分）<br/> 对于积分 [`MathIntegralTypes`](/slides/python-net/zh/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/zh/aspose.slides.mathtext/mathrowspacingrule/) | 矩阵或数组中列之间的垂直间距类型 |
| [`MathSpacingRules`](/slides/python-net/zh/aspose.slides.mathtext/mathspacingrules/) | 矩阵列之间的间隙（水平间距）类型 |
| [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions/) | 顶部/底部位置枚举 |
| [`MathVerticalAlignment`](/slides/python-net/zh/aspose.slides.mathtext/mathverticalalignment/) | 垂直对齐 |