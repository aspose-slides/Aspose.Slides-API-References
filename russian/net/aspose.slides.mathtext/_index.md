---
title: Aspose.Slides.MathText
second_title: Справочник по API Aspose.Slides для .NET
description: 
type: docs
weight: 120
url: /ru/net/aspose.slides.mathtext/
---
Содержит классы по работе с математическим текстом в презентациях Microsoft PowerPoint.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [BaseScript](./basescript) | Математический скрипт |
| [MathAccent](./mathaccent) | Указывает функцию ударения, состоящую из основы и комбинированного диакритического знака Пример:𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Позволяет создать математический акцент |
| [MathArray](./matharray) | Задает вертикальный массив уравнений или любых математических объектов |
| [MathArrayFactory](./matharrayfactory) | Позволяет создать математический массив |
| [MathBar](./mathbar) | Определяет функцию панели, состоящую из базового аргумента и верхней или нижней черты |
| [MathBarFactory](./mathbarfactory) | Позволяет создать математическую панель |
| [MathBlock](./mathblock) | Задает экземпляр математического текста, который содержится в MathParagraph и начинается на отдельной строке. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы представлены математическим блоком. |
| [MathBlockFactory](./mathblockfactory) | Позволяет создать математический блок |
| [MathBorderBox](./mathborderbox) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Позволяет создать математическую рамку |
| [MathBox](./mathbox) | Задает логическую упаковку (упаковку) математического элемента. Например, объект в штучной упаковке может служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть сгруппирован, чтобы не допускать разрывов строк. в пределах. Например, оператор "==" должен быть помещен в рамку, чтобы избежать разрывов строк. |
| [MathBoxFactory](./mathboxfactory) | Позволяет создать математическое поле |
| [MathDelimiter](./mathdelimiter) | Определяет объект-разделитель, состоящий из открывающих и закрывающих символов (таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или внутри больше математических элементов, разделенных указанным символом. Примеры:(𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Позволяет создать математический разделитель |
| [MathElementBase](./mathelementbase) | Базовый класс для IMathElement с реализацией некоторых методов, общих для всех унаследованных классов Только для внутреннего использования. Унаследованный класс должен быть IMathElement. |
| [MathematicalText](./mathematicaltext) | Математический текст |
| [MathematicalTextFactory](./mathematicaltextfactory) | Позволяет создать элемент MathematicalText |
| [MathFraction](./mathfraction) | Задает объект дроби, состоящий из числителя и знаменателя, разделенных чертой дроби. Полоса дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Объект дроби также используется для представления функции стека, которая размещает один элемент над другим, без дробной черты. |
| [MathFractionFactory](./mathfractionfactory) | Позволяет создать математическую дробь |
| [MathFunction](./mathfunction) | Задает функцию аргумента. |
| [MathFunctionFactory](./mathfunctionfactory) | Позволяет создать математическую функцию |
| [MathGroupingCharacter](./mathgroupingcharacter) | Указывает символ группировки над или под выражением, обычно для выделения связи между элементами |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Позволяет создать математический группирующий символ |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Определяет объект Sub-Superscript, который состоит из основания и нижнего и верхнего индексов, расположенных слева от основания. |
| [MathLimit](./mathlimit) | Определяет объект Limit, состоящий из текста на базовой линии и текста уменьшенного размера непосредственно над или под ним. |
| [MathLimitFactory](./mathlimitfactory) | Позволяет создать IMathLimit |
| [MathMatrix](./mathmatrix) | Задает объект Matrix, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Для помещения матрицы в скобки следует использовать объект-разделитель (IMathDelimiter). Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [MathMatrixFactory](./mathmatrixfactory) | Позволяет создать математическую матрицу |
| [MathNaryOperator](./mathnaryoperator) | Определяет N-арный математический объект, такой как Сумма и Интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхнего и нижнего пределов. Примеры N-арных операторов:Суммирование, Объединение, Пересечение, Интеграл |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Позволяет создать IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Математический абзац, являющийся контейнером для математических блоков (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Позволяет создать математический абзац |
| [MathPortion](./mathportion) | Представляет часть с математическим контекстом внутри. |
| [MathRadical](./mathradical) | Задает радикальную функцию, состоящую из основания и необязательной степени. Примером радикального объекта является √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Позволяет создавать математический радикал |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Определяет объект Sub-Superscript, который состоит из основания и нижнего и верхнего индексов, расположенных справа от основания. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Определяет объект нижнего индекса, который состоит из базового и нижнего индекса уменьшенного размера, расположенного ниже и правее. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Позволяет создавать IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Определяет объект надстрочного индекса, который состоит из основания и надстрочного индекса уменьшенного размера, расположенного выше и правее |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Позволяет создавать IMathSuperscriptElement |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IMathAccent](./imathaccent) | Указывает функцию ударения, состоящую из основы и комбинированного диакритического знака Пример:𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Позволяет создать математический акцент |
| [IMathArray](./imatharray) | Задает вертикальный массив уравнений или любых математических объектов |
| [IMathArrayFactory](./imatharrayfactory) | Позволяет создать математический массив |
| [IMathBar](./imathbar) | Определяет функцию панели, состоящую из базового аргумента и верхней или нижней черты |
| [IMathBarFactory](./imathbarfactory) | Позволяет создать математическую панель |
| [IMathBlock](./imathblock) | Задает экземпляр математического текста, который содержится в MathParagraph и начинается на отдельной строке. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы представлены математическим блоком. |
| [IMathBlockCollection](./imathblockcollection) | Коллекция математических блоков (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Позволяет создать математический блок |
| [IMathBorderBox](./imathborderbox) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Позволяет создать математическую рамку |
| [IMathBox](./imathbox) | Задает логическую упаковку (упаковку) математического элемента. Например, объект в штучной упаковке может служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть сгруппирован, чтобы не допускать разрывов строк. в пределах. Например, оператор "==" должен быть помещен в рамку, чтобы избежать разрывов строк. |
| [IMathBoxFactory](./imathboxfactory) | Позволяет создать математическое поле |
| [IMathDelimiter](./imathdelimiter) | Определяет объект-разделитель, состоящий из открывающих и закрывающих символов (таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или внутри больше математических элементов, разделенных указанным символом. Примеры:(𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Позволяет создать математический разделитель |
| [IMathElement](./imathelement) | Базовый интерфейс любого математического элемента: дробь, математический текст, функция, выражение с несколькими элементами и т. д. |
| [IMathElementCollection](./imathelementcollection) | Представляет набор математических элементов (MathElement). |
| [IMathematicalText](./imathematicaltext) | Математический текст |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Позволяет создать элемент MathematicalText |
| [IMathFraction](./imathfraction) | Задает объект дроби, состоящий из числителя и знаменателя, разделенных чертой дроби. Полоса дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Объект дроби также используется для представления функции стека, которая размещает один элемент над другим, без дробной черты. |
| [IMathFractionFactory](./imathfractionfactory) | Позволяет создать математическую дробь |
| [IMathFunction](./imathfunction) | Задает функцию аргумента. |
| [IMathFunctionFactory](./imathfunctionfactory) | Позволяет создать математическую функцию |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Указывает символ группировки над или под выражением, обычно для выделения связи между элементами |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Позволяет создать математический группирующий символ |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Определяет объект Sub-Superscript, который состоит из основания и нижнего и верхнего индексов, расположенных слева от основания. |
| [IMathLimit](./imathlimit) | Определяет объект Limit, состоящий из текста на базовой линии и текста уменьшенного размера непосредственно над или под ним. |
| [IMathLimitFactory](./imathlimitfactory) | Позволяет создать IMathLimit |
| [IMathMatrix](./imathmatrix) | Задает объект Matrix, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Для помещения матрицы в скобки следует использовать объект-разделитель (IMathDelimiter). Нулевые аргументы могут использоваться для создания пробелов в матрицах. |
| [IMathMatrixFactory](./imathmatrixfactory) | Позволяет создать математическую матрицу |
| [IMathNaryOperator](./imathnaryoperator) | Определяет N-арный математический объект, такой как Сумма и Интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхнего и нижнего пределов. Примеры N-арных операторов:Суммирование, Объединение, Пересечение, Интеграл |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Позволяет создать IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Задает свойства IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Математический абзац, являющийся контейнером для математических блоков (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Позволяет создать математический абзац |
| [IMathPortion](./imathportion) | Представляет часть с математическим контекстом внутри. |
| [IMathRadical](./imathradical) | Задает радикальную функцию, состоящую из основания и необязательной степени. Примером радикального объекта является √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Позволяет создавать математический радикал |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Определяет объект Sub-Superscript, который состоит из основания и нижнего и верхнего индексов, расположенных справа от основания. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Определяет объект нижнего индекса, который состоит из базового и нижнего индекса уменьшенного размера, расположенного ниже и правее. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Позволяет создавать IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Определяет объект надстрочного индекса, который состоит из основания и надстрочного индекса уменьшенного размера, расположенного выше и правее |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Позволяет создавать IMathSuperscriptElement |
## перечисление

| перечисление | Описание |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Расположение и размер разделителей относительно содержимого операндов |
| [MathFractionTypes](./mathfractiontypes) | Типы дробей |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Общие математические функции одного аргумента |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Общие математические функции двух аргументов |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Выравнивание по горизонтали |
| [MathIntegralTypes](./mathintegraltypes) | Типы математических интегралов |
| [MathJustification](./mathjustification) | Задает выравнивание математического абзаца (ряд смежных экземпляров математического текста в одном абзаце) |
| [MathLimitLocations](./mathlimitlocations) | Расположение пределов (индекс/верхний индекс) в n-арных операторах. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Нарный оператор Типы IMathNaryOperator (исключая интегралы) Для интегралов[`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Тип интервала по вертикали между столбцами в матрице или массиве |
| [MathSpacingRules](./mathspacingrules) | Типы зазоров (горизонтальных интервалов) между столбцами матрицы |
| [MathTopBotPositions](./mathtopbotpositions) | Перечисление верхних/нижних позиций |
| [MathVerticalAlignment](./mathverticalalignment) | Выравнивание по вертикали |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
