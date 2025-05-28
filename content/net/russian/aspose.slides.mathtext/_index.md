---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes для .NET API Reference
description: Содержит классы для работы с математическим текстом в презентациях Microsoft PowerPoint.
type: docs
weight: 120
url: /ru/aspose.slides.mathtext/
---

Содержит классы для работы с математическим текстом в презентациях Microsoft PowerPoint.

## Классы

| Класс | Описание |
| --- | --- |
| [BaseScript](./basescript) | Математический скрипт |
| [MathAccent](./mathaccent) | Указывает функцию акцента, состоящую из базы и комбинирующего диакритического знака. Пример: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Позволяет создать математический акцент |
| [MathArray](./matharray) | Указывает вертикальный массив уравнений или любых математических объектов |
| [MathArrayFactory](./matharrayfactory) | Позволяет создать математический массив |
| [MathBar](./mathbar) | Указывает функцию бар, состоящую из базового аргумента и надстрочного или подстрочного знака |
| [MathBarFactory](./mathbarfactory) | Позволяет создать математическую линию |
| [MathBlock](./mathblock) | Указывает экземпляр математического текста, который содержится в MathParagraph и начинается с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком. |
| [MathBlockFactory](./mathblockfactory) | Позволяет создать математический блок |
| [MathBorderBox](./mathborderbox) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Позволяет создать границу для математических объектов |
| [MathBox](./mathbox) | Указывает логическую упаковку математического элемента. Например, упакованный объект может служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован таким образом, чтобы не допускать разрывов строк внутри. Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строк. |
| [MathBoxFactory](./mathboxfactory) | Позволяет создать математическую коробку |
| [MathDelimiter](./mathdelimiter) | Указывает объект-разделитель, состоящий из открывающих и закрывающих символов (таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или нескольких математических элементов внутри, разделенных указанным символом. Примеры: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Позволяет создать математический разделитель |
| [MathElementBase](./mathelementbase) | Базовый класс для IMathElement с реализацией некоторых методов, общих для всех наследуемых классов. Только для внутреннего использования. Наследуемый класс должен быть IMathElement. |
| [MathematicalText](./mathematicaltext) | Математический текст |
| [MathematicalTextFactory](./mathematicaltextfactory) | Позволяет создать элемент MathematicalText |
| [MathFraction](./mathfraction) | Указывает объект дроби, состоящий из числителя и знаменателя, разделенных дробной линией. Дробная линия может быть горизонтальной или диагональной в зависимости от свойств дроби. Объект дроби также используется для представления стековой функции, которая помещает один элемент над другим без дробной линии. |
| [MathFractionFactory](./mathfractionfactory) | Позволяет создать математическую дробь |
| [MathFunction](./mathfunction) | Указывает функцию аргумента. |
| [MathFunctionFactory](./mathfunctionfactory) | Позволяет создать математическую функцию |
| [MathGroupingCharacter](./mathgroupingcharacter) | Указывает символ группировки над или под выражением, обычно чтобы выделить связь между элементами |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Позволяет создать символ группировки для математики |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Указывает объект под- и надстрочной записи, который состоит из базы и подстрочного и надстрочного знаков, размещенных слева от базы. |
| [MathLimit](./mathlimit) | Указывает объект лимита, состоящий из текста на базовой линии и текста уменьшенного размера непосредственно выше или ниже его. |
| [MathLimitFactory](./mathlimitfactory) | Позволяет создать IMathLimit |
| [MathMatrix](./mathmatrix) | Указывает объект матрицы, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект-разделитель (IMathDelimiter). Параметры null можно использовать для создания пробелов в матрицах. |
| [MathMatrixFactory](./mathmatrixfactory) | Позволяет создать математическую матрицу |
| [MathNaryOperator](./mathnaryoperator) | Указывает N-арный математический объект, такой как Суммирование и Интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Суммирование, Объединение, Пересечение, Интеграл |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Позволяет создать IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Математический параграф, который является контейнером для математических блоков (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Позволяет создать математический параграф |
| [MathPortion](./mathportion) | Представляет часть с математическим контекстом внутри. |
| [MathRadical](./mathradical) | Указывает радикальную функцию, состоящую из базы и необязательной степени. Пример радикального объекта: √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Позволяет создать математический радикал |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Указывает объект под- и надстрочной записи, который состоит из базы и подстрочного и надстрочного знаков, размещенных справа от базы. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Указывает объект подстрочного знака, который состоит из базы и уменьшенного размера подстрока, размещенного ниже и справа. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Позволяет создать IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Указывает объект надстрочного знака, который состоит из базы и уменьшенного размера надстрока, размещенного выше и справа |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Позволяет создать IMathSuperscriptElement |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IMathAccent](./imathaccent) | Указывает функцию акцента, состоящую из базы и комбинирующего диакритического знака. Пример: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Позволяет создать математический акцент |
| [IMathArray](./imatharray) | Указывает вертикальный массив уравнений или любых математических объектов |
| [IMathArrayFactory](./imatharrayfactory) | Позволяет создать математический массив |
| [IMathBar](./imathbar) | Указывает функцию бар, состоящую из базового аргумента и надстрочного или подстрочного знака |
| [IMathBarFactory](./imathbarfactory) | Позволяет создать математическую линию |
| [IMathBlock](./imathblock) | Указывает экземпляр математического текста, который содержится в MathParagraph и начинается с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком. |
| [IMathBlockCollection](./imathblockcollection) | Коллекция математических блоков (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Позволяет создать математический блок |
| [IMathBorderBox](./imathborderbox) | Рисует прямоугольную или другую границу вокруг IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Позволяет создать границу для математических объектов |
| [IMathBox](./imathbox) | Указывает логическую упаковку математического элемента. Например, упакованный объект может служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован таким образом, чтобы не допускать разрывов строк внутри. Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строк. |
| [IMathBoxFactory](./imathboxfactory) | Позволяет создать математическую коробку |
| [IMathDelimiter](./imathdelimiter) | Указывает объект-разделитель, состоящий из открывающих и закрывающих символов (таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или нескольких математических элементов внутри, разделенных указанным символом. Примеры: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Позволяет создать математический разделитель |
| [IMathElement](./imathelement) | Базовый интерфейс любого математического элемента: дробь, математический текст, функция, выражение с несколькими элементами и т.д. |
| [IMathElementCollection](./imathelementcollection) | Представляет коллекцию математических элементов (MathElement). |
| [IMathematicalText](./imathematicaltext) | Математический текст |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Позволяет создать элемент MathematicalText |
| [IMathFraction](./imathfraction) | Указывает объект дроби, состоящий из числителя и знаменателя, разделенных дробной линией. Дробная линия может быть горизонтальной или диагональной в зависимости от свойств дроби. Объект дроби также используется для представления стековой функции, которая помещает один элемент над другим без дробной линии. |
| [IMathFractionFactory](./imathfractionfactory) | Позволяет создать математическую дробь |
| [IMathFunction](./imathfunction) | Указывает функцию аргумента. |
| [IMathFunctionFactory](./imathfunctionfactory) | Позволяет создать математическую функцию |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Указывает символ группировки над или под выражением, обычно чтобы выделить связь между элементами |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Позволяет создать символ группировки для математики |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Указывает объект под- и надстрочной записи, который состоит из базы и подстрочного и надстрочного знаков, размещенных слева от базы. |
| [IMathLimit](./imathlimit) | Указывает объект лимита, состоящий из текста на базовой линии и текста уменьшенного размера непосредственно выше или ниже его. |
| [IMathLimitFactory](./imathlimitfactory) | Позволяет создать IMathLimit |
| [IMathMatrix](./imathmatrix) | Указывает объект матрицы, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект-разделитель (IMathDelimiter). Параметры null можно использовать для создания пробелов в матрицах. |
| [IMathMatrixFactory](./imathmatrixfactory) | Позволяет создать математическую матрицу |
| [IMathNaryOperator](./imathnaryoperator) | Указывает N-арный математический объект, такой как Суммирование и Интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Суммирование, Объединение, Пересечение, Интеграл |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Позволяет создать IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Указывает свойства IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Математический параграф, который является контейнером для математических блоков (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Позволяет создать математический параграф |
| [IMathPortion](./imathportion) | Представляет часть с математическим контекстом внутри. |
| [IMathRadical](./imathradical) | Указывает радикальную функцию, состоящую из базы и необязательной степени. Пример радикального объекта: √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Позволяет создать математический радикал |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Указывает объект под- и надстрочной записи, который состоит из базы и подстрочного и надстрочного знаков, размещенных справа от базы. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Позволяет создать IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Указывает объект подстрочного знака, который состоит из базы и уменьшенного размера подстрока, размещенного ниже и справа. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Позволяет создать IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Указывает объект надстрочного знака, который состоит из базы и уменьшенного размера надстрока, размещенного выше и справа |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Позволяет создать IMathSuperscriptElement |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Расположение и размер разделителей относительно содержимого операндов |
| [MathFractionTypes](./mathfractiontypes) | Типы дробей |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Общие математические функции с одним аргументом |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Общие математические функции с двумя аргументами |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Горизонтальное выравнивание |
| [MathIntegralTypes](./mathintegraltypes) | Типы математических интегралов |
| [MathJustification](./mathjustification) | Указывает выравнивание математического параграфа (серия смежных экземпляров математического текста в одном параграфе) |
| [MathLimitLocations](./mathlimitlocations) | Расположение пределов (подстрок/надстрок) в N-арных операторах. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Типы N-арных операторов IMathNaryOperator (исключая интегралы). Для интегралов [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Тип вертикального расстояния между столбцами в матрице или массиве |
| [MathSpacingRules](./mathspacingrules) | Типы зазора (горизонтальное расстояние) между столбцами матрицы |
| [MathTopBotPositions](./mathtopbotpositions) | Перечисление верхних/нижних позиций |
| [MathVerticalAlignment](./mathverticalalignment) | Вертикальное выравнивание |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->