---
title: aspose.slides.mathtext
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/
---
Содержит классы для работы с математическим текстом в презентациях Microsoft PowerPoint.
## Классы

| Класс | Описание |
| :- | :- |
| [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript/) | Math script |
| [`IMathAccent`](/slides/python-net/ru/aspose.slides.mathtext/imathaccent/) | Указывает функцию акцента, состоящую из базового символа и объединяющего диакритического знака<br/>            Пример: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathaccentfactory/) | Позволяет создать математический акцент |
| [`IMathArray`](/slides/python-net/ru/aspose.slides.mathtext/imatharray/) | Указывает вертикальный массив уравнений или любых математических объектов |
| [`IMathArrayFactory`](/slides/python-net/ru/aspose.slides.mathtext/imatharrayfactory/) | Позволяет создать математический массив |
| [`IMathBar`](/slides/python-net/ru/aspose.slides.mathtext/imathbar/) | Указывает функцию линии, состоящую из базового аргумента и надчеркивания или подчеркивания |
| [`IMathBarFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathbarfactory/) | Позволяет создать математическую линию |
| [`IMathBlock`](/slides/python-net/ru/aspose.slides.mathtext/imathblock/) | Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки.<br/>            Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены как математический блок. |
| [`IMathBlockCollection`](/slides/python-net/ru/aspose.slides.mathtext/imathblockcollection/) | Коллекция математических блоков (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathblockfactory/) | Позволяет создать математический блок |
| [`IMathBorderBox`](/slides/python-net/ru/aspose.slides.mathtext/imathborderbox/) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathborderboxfactory/) | Позволяет создать математическую рамку |
| [`IMathBox`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/) | Указывает логическое упаковывание (boxing) математического элемента.<br/>            Например, заключённый в рамку объект может выступать в роли эмулятора оператора с точкой выравнивания или без неё,<br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри.<br/>            Например, оператор "==" следует заключить в рамку, чтобы предотвратить разрывы строк. |
| [`IMathBoxFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathboxfactory/) | Позволяет создать математическую рамку |
| [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter/) | Указывает объект-разделитель, состоящий из открывающих и закрывающих символов (например, скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или нескольких математических элементов внутри, разделённых указанным символом.<br/>            Примеры: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiterfactory/) | Позволяет создать математический разделитель |
| [`IMathElement`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/) | Базовый интерфейс любого математического элемента:<br/>            дробь, математический текст, функция, выражение с несколькими элементами и т.д. |
| [`IMathElementCollection`](/slides/python-net/ru/aspose.slides.mathtext/imathelementcollection/) | Представляет коллекцию математических элементов (MathElement). |
| [`IMathFraction`](/slides/python-net/ru/aspose.slides.mathtext/imathfraction/) | Указывает объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби.<br/>            Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби.<br/>            Объект дроби также используется для представления функции стека, которая размещает один элемент над другим без черты дроби. |
| [`IMathFractionFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathfractionfactory/) | Позволяет создать математическую дробь |
| [`IMathFunction`](/slides/python-net/ru/aspose.slides.mathtext/imathfunction/) | Указывает функцию аргумента. |
| [`IMathFunctionFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathfunctionfactory/) | Позволяет создать математическую функцию |
| [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter/) | Указывает символ группировки над или под выражением, обычно для выделения взаимосвязи между элементами |
| [`IMathGroupingCharacterFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Позволяет создать символ группировки |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Указывает объект нижнего/верхнего индекса, который состоит из базы<br/>            и нижнего и верхнего индексов, размещённых слева от базы. |
| [`IMathLimit`](/slides/python-net/ru/aspose.slides.mathtext/imathlimit/) | Указывает объект предела, состоящий из текста на базовой линии и уменьшенного текста сразу выше или ниже её. |
| [`IMathLimitFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathlimitfactory/) | Позволяет создать IMathLimit |
| [`IMathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/) | Указывает объект матрицы, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах.<br/>            Важно отметить, что у матриц нет встроенных разделителей.<br/>            Чтобы разместить матрицу в скобках, следует использовать объект-разделитель (IMathDelimiter).<br/>            Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [`IMathMatrixFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrixfactory/) | Позволяет создать математическую матрицу |
| [`IMathNaryOperator`](/slides/python-net/ru/aspose.slides.mathtext/imathnaryoperator/) | Указывает N-арный математический объект, такой как сумма или интеграл.<br/>            Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов.<br/>            Примеры N-арных операторов: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathnaryoperatorfactory/) | Позволяет создать IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/ru/aspose.slides.mathtext/imathnaryoperatorproperties/) | Указывает свойства IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/ru/aspose.slides.mathtext/imathparagraph/) | Математический абзац, являющийся контейнером для математических блоков (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathparagraphfactory/) | Позволяет создать математический абзац |
| [`IMathPhantom`](/slides/python-net/ru/aspose.slides.mathtext/imathphantom/) | Представляет фантомный математический объект (<m:phant>), влияющий на расположение дочернего элемента<br/>            без обязательного отображения его. Фантом может скрыть базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования места.<br/>            Видимость и геометрическое поведение контролируются свойствами, такими как Show, ZeroWid, ZeroAsc,<br/>            ZeroDesc и Transp. |
| [`IMathPortion`](/slides/python-net/ru/aspose.slides.mathtext/imathportion/) | Представляет часть с математическим контекстом внутри. |
| [`IMathRadical`](/slides/python-net/ru/aspose.slides.mathtext/imathradical/) | Указывает радикальную функцию, состоящую из базы и необязательной степени.<br/>            Пример радикального объекта: √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathradicalfactory/) | Позволяет создать радикал |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Указывает объект нижнего/верхнего индекса, который состоит из базы<br/>            и нижнего и верхнего индексов, размещённых справа от базы. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/imathsubscriptelement/) | Указывает объект нижнего индекса, который состоит из базы<br/>            и уменьшенного нижнего индекса, размещённого снизу и справа. |
| [`IMathSubscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathsubscriptelementfactory/) | Позволяет создать IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/imathsuperscriptelement/) | Указывает объект верхнего индекса, который состоит из базы<br/>            и уменьшенного верхнего индекса, размещённого сверху и справа |
| [`IMathSuperscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Позволяет создать IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/ru/aspose.slides.mathtext/imathematicaltext/) | Математический текст |
| [`IMathematicalTextFactory`](/slides/python-net/ru/aspose.slides.mathtext/imathematicaltextfactory/) | Позволяет создать элемент MathematicalText |
| [`MathAccent`](/slides/python-net/ru/aspose.slides.mathtext/mathaccent/) | Указывает функцию акцента, состоящую из базового символа и объединяющего диакритического знака<br/>            Пример: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathaccentfactory/) | Позволяет создать математический акцент |
| [`MathArray`](/slides/python-net/ru/aspose.slides.mathtext/matharray/) | Указывает вертикальный массив уравнений или любых математических объектов |
| [`MathArrayFactory`](/slides/python-net/ru/aspose.slides.mathtext/matharrayfactory/) | Позволяет создать математический массив |
| [`MathBar`](/slides/python-net/ru/aspose.slides.mathtext/mathbar/) | Указывает функцию линии, состоящую из базового аргумента и надчеркивания или подчеркивания |
| [`MathBarFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathbarfactory/) | Позволяет создать математическую линию |
| [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/) | Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки.<br/>            Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены как математический блок. |
| [`MathBlockFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathblockfactory/) | Позволяет создать математический блок |
| [`MathBorderBox`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathborderboxfactory/) | Позволяет создать математическую рамку |
| [`MathBox`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/) | Указывает логическое упаковывание (boxing) математического элемента.<br/>            Например, заключённый в рамку объект может выступать в роли эмулятора оператора с точкой выравнивания или без неё,<br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри.<br/>            Например, оператор "==" следует заключить в рамку, чтобы предотвратить разрывы строк. |
| [`MathBoxFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathboxfactory/) | Позволяет создать математическую рамку |
| [`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/) | Указывает объект-разделитель, состоящий из открывающих и закрывающих символов (например, скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или нескольких математических элементов внутри, разделённых указанным символом.<br/>            Примеры: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiterfactory/) | Позволяет создать математический разделитель |
| [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase/) | Базовый класс для IMathElement с реализацией некоторых методов, общих для всех наследуемых классов<br/>            Только для внутреннего использования. Наследуемый класс должен быть IMathElement. |
| [`MathFraction`](/slides/python-net/ru/aspose.slides.mathtext/mathfraction/) | Указывает объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби.<br/>            Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби.<br/>            Объект дроби также используется для представления функции стека, которая размещает один элемент над другим без черты дроби. |
| [`MathFractionFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathfractionfactory/) | Позволяет создать математическую дробь |
| [`MathFunction`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/) | Указывает функцию аргумента. |
| [`MathFunctionFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathfunctionfactory/) | Позволяет создать математическую функцию |
| [`MathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/mathgroupingcharacter/) | Указывает символ группировки над или под выражением, обычно для выделения взаимосвязи между элементами |
| [`MathGroupingCharacterFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Позволяет создать символ группировки |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Указывает объект нижнего/верхнего индекса, который состоит из базы<br/>            и нижнего и верхнего индексов, размещённых слева от базы. |
| [`MathLimit`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/) | Указывает объект предела, состоящий из текста на базовой линии и уменьшенного текста сразу выше или ниже её. |
| [`MathLimitFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathlimitfactory/) | Позволяет создать IMathLimit |
| [`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/) | Указывает объект матрицы, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах.<br/>            Важно отметить, что у матриц нет встроенных разделителей.<br/>            Чтобы разместить матрицу в скобках, следует использовать объект-разделитель (IMathDelimiter).<br/>            Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [`MathMatrixFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrixfactory/) | Позволяет создать математическую матрицу |
| [`MathNaryOperator`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/) | Указывает N-арный математический объект, такой как сумма или интеграл.<br/>            Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов.<br/>            Примеры N-арных операторов: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperatorfactory/) | Позволяет создать IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/ru/aspose.slides.mathtext/mathparagraph/) | Математический абзац, являющийся контейнером для математических блоков (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathparagraphfactory/) | Позволяет создать математический абзац |
| [`MathPhantom`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/) | Представляет фантомный математический объект (<m:phant>), влияющий на расположение дочернего элемента<br/>            без обязательного отображения его. Фантом может скрыть базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования места.<br/>            Видимость и геометрическое поведение контролируются свойствами, такими как Show, ZeroWid, ZeroAsc,<br/>            ZeroDesc и Transp. |
| [`MathPortion`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/) | Представляет часть с математическим контекстом внутри. |
| [`MathRadical`](/slides/python-net/ru/aspose.slides.mathtext/mathradical/) | Указывает радикальную функцию, состоящую из базы и необязательной степени.<br/>            Пример радикального объекта: √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathradicalfactory/) | Позволяет создать радикал |
| [`MathRightSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Указывает объект нижнего/верхнего индекса, который состоит из базы<br/>            и нижнего и верхнего индексов, размещённых справа от базы. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/) | Указывает объект нижнего индекса, который состоит из базы<br/>            и уменьшенного нижнего индекса, размещённого снизу и справа. |
| [`MathSubscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelementfactory/) | Позволяет создать IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/) | Указывает объект верхнего индекса, который состоит из базы<br/>            и уменьшенного верхнего индекса, размещённого сверху и справа |
| [`MathSuperscriptElementFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Позволяет создать IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/ru/aspose.slides.mathtext/mathematicaltext/) | Математический текст |
| [`MathematicalTextFactory`](/slides/python-net/ru/aspose.slides.mathtext/mathematicaltextfactory/) | Позволяет создать элемент MathematicalText |

## Перечисления

| Перечисление | Описание |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimitershape/) | Положение и размер разделителей относительно содержимого операндов |
| [`MathFractionTypes`](/slides/python-net/ru/aspose.slides.mathtext/mathfractiontypes/) | Типы дробей |
| [`MathFunctionsOfOneArgument`](/slides/python-net/ru/aspose.slides.mathtext/mathfunctionsofoneargument/) | Общие математические функции с одним аргументом |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/ru/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Общие математические функции с двумя аргументами |
| [`MathHorizontalAlignment`](/slides/python-net/ru/aspose.slides.mathtext/mathhorizontalalignment/) | Горизонтальное выравнивание |
| [`MathIntegralTypes`](/slides/python-net/ru/aspose.slides.mathtext/mathintegraltypes/) | Типы математических интегралов |
| [`MathJustification`](/slides/python-net/ru/aspose.slides.mathtext/mathjustification/) | Указывает выравнивание математического абзаца (последовательность смежных экземпляров математического текста в одном абзаце) |
| [`MathLimitLocations`](/slides/python-net/ru/aspose.slides.mathtext/mathlimitlocations/) | Положение пределов (нижний/верхний индекс) в N-арных операторах. |
| [`MathNaryOperatorTypes`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperatortypes/) | Типы N-арных операторов IMathNaryOperator (за исключением интегралов)<br/>            Для интегралов [`MathIntegralTypes`](/slides/python-net/ru/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/ru/aspose.slides.mathtext/mathrowspacingrule/) | Тип вертикального расстояния между столбцами в матрице или массиве |
| [`MathSpacingRules`](/slides/python-net/ru/aspose.slides.mathtext/mathspacingrules/) | Типы зазоров (горизонтального расстояния) между столбцами матрицы |
| [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions/) | Перечисление верхних/нижних позиций |
| [`MathVerticalAlignment`](/slides/python-net/ru/aspose.slides.mathtext/mathverticalalignment/) | Вертикальное выравнивание |