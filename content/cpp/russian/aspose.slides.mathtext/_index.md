---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides для C++ справочник API
description: 
type: docs
weight: 157
url: /ru/aspose.slides.mathtext/
---
## Классы

| Класс | Описание |
| --- | --- |
| [BaseScript](./basescript/) | Математический скрипт |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) с [Control](../aspose.slides/control/) свойствами символов |
| [IMathAccent](./imathaccent/) | Определяет функцию акцента, состоящую из базового элемента и комбинирующего диакритического знака. Пример: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Позволяет создать математический акцент |
| [IMathArray](./imatharray/) | Определяет вертикальный массив уравнений или любых математических объектов |
| [IMathArrayFactory](./imatharrayfactory/) | Позволяет создать математический массив |
| [IMathBar](./imathbar/) | Определяет функцию черты, состоящую из базового аргумента и надчёркивания или подчёркивания |
| [IMathBarFactory](./imathbarfactory/) | Позволяет создать математическую черту |
| [IMathBlock](./imathblock/) | Определяет экземпляр математического текста, содержащегося внутри [MathParagraph](./mathparagraph/) и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представляются как математический блок. |
| [IMathBlockCollection](./imathblockcollection/) | Коллекция математических блоков ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Позволяет создать математический блок |
| [IMathBorderBox](./imathborderbox/) | Рисует прямоугольную или другую рамку вокруг [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Позволяет создать математическую рамку |
| [IMathBox](./imathbox/) | Определяет логическое упаковку (упаковку) математического элемента. Например, объект в коробке может служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри. Например, оператор \"==\" должен быть упакован, чтобы предотвратить разрывы строк. |
| [IMathBoxFactory](./imathboxfactory/) | Позволяет создать математическую коробку |
| [IMathDelimiter](./imathdelimiter/) | Определяет объект-разделитель, состоящий из открывающих и закрывающих символов (например, скобки, фигурные скобки, квадратные скобки и вертикальные черты), и одного или нескольких математических элементов внутри, разделённых указанным символом. Примеры: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Позволяет создать математический разделитель |
| [IMathElement](./imathelement/) | Базовый интерфейс любого математического элемента: дроби, математического текста, функции, выражения с несколькими элементами и т.д. |
| [IMathElementCollection](./imathelementcollection/) | Представляет коллекцию математических элементов (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Математический текст |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Позволяет создать элемент [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Определяет объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби. Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Объект дроби также используется для представления функции стека, которая размещает один элемент над другим без черты дроби. |
| [IMathFractionFactory](./imathfractionfactory/) | Позволяет создать математическую дробь |
| [IMathFunction](./imathfunction/) | Определяет функцию аргумента. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Позволяет создать математическую функцию |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Определяет символ группировки над или под выражением, обычно для выделения взаимосвязи между элементами |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Позволяет создать символ группировки в математике |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Определяет объект под- и надстрочного знака, который состоит из базового элемента и подстрочного и надстрочного знаков, размещённых слева от базы. |
| [IMathLimit](./imathlimit/) | Определяет объект предела, состоящий из текста на базовой линии и уменьшенного текста сразу над или под ней. |
| [IMathLimitFactory](./imathlimitfactory/) | Позволяет создать [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Определяет объект матрицы, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что у матриц нет встроенных разделителей. Чтобы разместить матрицу в скобках, следует использовать объект-разделитель ([IMathDelimiter](./imathdelimiter/)). Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Позволяет создать математическую матрицу |
| [IMathNaryOperator](./imathnaryoperator/) | Определяет N-арный математический объект, такой как Summation и Integral. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Summation, Union, Intersection, Integral. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Позволяет создать [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Определяет свойства [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Математический абзац, который является контейнером для математических блоков ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Позволяет создать математический абзац |
| [IMathPhantom](./imathphantom/) | Представляет «призрачный» математический объект (<m:phant>), который влияет на расположение дочерних элементов, не обязательно отображаясь. Призрак может скрывать базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования места. Видимость и поведение геометрии управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp. |
| [IMathPortion](./imathportion/) | Представляет часть с математическим контекстом внутри. |
| [IMathRadical](./imathradical/) | Определяет радикальную функцию, состоящую из базы и необязательной степени. Пример радикального объекта: \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Позволяет создать математический радикал |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Определяет объект под- и надстрочного знака, который состоит из базового элемента и подстрочного и надстрочного знаков, размещённых справа от базы. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Позволяет создать [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Определяет объект подстрочного знака, который состоит из базового элемента и уменьшенного подстрочного знака, размещённого снизу и справа. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Позволяет создать [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Определяет объект надстрочного знака, который состоит из базового элемента и уменьшенного надстрочного знака, размещённого сверху и справа |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Позволяет создать [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Определяет функцию акцента, состоящую из базового элемента и комбинирующего диакритического знака. Пример: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Позволяет создать математический акцент |
| [MathArray](./matharray/) | Определяет вертикальный массив уравнений или любых математических объектов |
| [MathArrayFactory](./matharrayfactory/) | Позволяет создать математический массив |
| [MathBar](./mathbar/) | Определяет функцию черты, состоящую из базового аргумента и надчёркивания или подчёркивания |
| [MathBarFactory](./mathbarfactory/) | Позволяет создать математическую черту |
| [MathBlock](./mathblock/) | Определяет экземпляр математического текста, содержащегося внутри [MathParagraph](./mathparagraph/) и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представляются как математический блок. |
| [MathBlockFactory](./mathblockfactory/) | Позволяет создать математический блок |
| [MathBorderBox](./mathborderbox/) | Рисует прямоугольную или другую рамку вокруг [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Позволяет создать математическую рамку |
| [MathBox](./mathbox/) | Определяет логическое упаковку (упаковку) математического элемента. Например, объект в коробке может служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри. Например, оператор \"==\" должен быть упакован, чтобы предотвратить разрывы строк. |
| [MathBoxFactory](./mathboxfactory/) | Позволяет создать математическую коробку |
| [MathDelimiter](./mathdelimiter/) | Определяет объект-разделитель, состоящий из открывающих и закрывающих символов (например, скобки, фигурные скобки, квадратные скобки и вертикальные черты), и одного или нескольких математических элементов внутри, разделённых указанным символом. Примеры: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Позволяет создать математический разделитель |
| [MathElementBase](./mathelementbase/) | Базовый класс для [IMathElement](./imathelement/) с реализацией некоторых методов, общих для всех наследуемых классов. Только для внутреннего использования. Наследующий класс должен быть [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Математический текст |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Позволяет создать элемент [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Определяет объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби. Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Объект дроби также используется для представления функции стека, которая размещает один элемент над другим без черты дроби. |
| [MathFractionFactory](./mathfractionfactory/) | Позволяет создать математическую дробь |
| [MathFunction](./mathfunction/) | Определяет функцию аргумента. |
| [MathFunctionFactory](./mathfunctionfactory/) | Позволяет создать математическую функцию |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Определяет символ группировки над или под выражением, обычно для выделения взаимосвязи между элементами |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Позволяет создать символ группировки в математике |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Определяет объект под- и надстрочного знака, который состоит из базового элемента и подстрочного и надстрочного знаков, размещённых слева от базы. |
| [MathLimit](./mathlimit/) | Определяет объект предела, состоящий из текста на базовой линии и уменьшенного текста сразу над или под ней. |
| [MathLimitFactory](./mathlimitfactory/) | Позволяет создать [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Определяет объект матрицы, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что у матриц нет встроенных разделителей. Чтобы разместить матрицу в скобках, следует использовать объект-разделитель ([IMathDelimiter](./imathdelimiter/)). Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [MathMatrixFactory](./mathmatrixfactory/) | Позволяет создать математическую матрицу |
| [MathNaryOperator](./mathnaryoperator/) | Определяет N-арный математический объект, такой как Summation и Integral. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Summation, Union, Intersection, Integral. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Позволяет создать [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Математический абзац, который является контейнером для математических блоков ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Позволяет создать математический абзац |
| [MathPhantom](./mathphantom/) | Представляет «призрачный» математический объект (<m:phant>), который влияет на расположение дочерних элементов, не обязательно отображаясь. Призрак может скрывать базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования места. Видимость и поведение геометрии управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp. |
| [MathPortion](./mathportion/) | Представляет часть с математическим контекстом внутри. |
| [MathRadical](./mathradical/) | Определяет радикальную функцию, состоящую из базы и необязательной степени. Пример радикального объекта: \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Позволяет создать математический радикал |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Определяет объект под- и надстрочного знака, который состоит из базового элемента и подстрочного и надстрочного знаков, размещённых справа от базы. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Позволяет создать [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Определяет объект подстрочного знака, который состоит из базового элемента и уменьшенного подстрочного знака, размещённого снизу и справа. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Позволяет создать [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Определяет объект надстрочного знака, который состоит из базового элемента и уменьшенного надстрочного знака, размещённого сверху и справа |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Позволяет создать [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Расположение и размер разделителей относительно содержимого операндов |
| [MathFractionTypes](./mathfractiontypes/) | Типы дробей |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Общие математические функции одного аргумента |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Общие математические функции двух аргументов |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Горизонтальное выравнивание |
| [MathIntegralTypes](./mathintegraltypes/) | Типы математических интегралов |
| [MathJustification](./mathjustification/) | Определяет выравнивание математического абзаца (последовательность смежных экземпляров математического текста в одном абзаце) |
| [MathLimitLocations](./mathlimitlocations/) | Расположение пределов (подстрочный/надстрочный) в n-арных операторах. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Типы n-арных операторов [IMathNaryOperator](./imathnaryoperator/) (за исключением интегралов). Для интегралов [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Тип вертикального интервала между столбцами в матрице или массиве |
| [MathSpacingRules](./mathspacingrules/) | Типы зазоров (горизонтального интервала) между столбцами матрицы |
| [MathTopBotPositions](./mathtopbotpositions/) | Перечисление позиций верх/низ |
| [MathVerticalAlignment](./mathverticalalignment/) | Вертикальное выравнивание |