---
title: MathNaryOperator
second_title: Aspose.Sildes для .NET API Reference
description: Указывает N-арный математический объект, такой как Суммирование и Интеграл. Он состоит из оператора, основы или операнда и необязательных верхних и нижних пределов. Примеры N-арных операторов Суммирование, Объединение, Пересечение, Интеграл
type: docs
weight: 8610
url: /ru/aspose.slides.mathtext/mathnaryoperator/
---

## MathNaryOperator класс

Указывает N-арный математический объект, такой как Суммирование и Интеграл. Он состоит из оператора, основы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Суммирование, Объединение, Пересечение, Интеграл

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Инициализирует новый экземпляр класса MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Инициализирует новый экземпляр класса MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Инициализирует новый экземпляр класса MathNaryOperator. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Аргумент основы |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Символ оператора растет вертикально, чтобы соответствовать высоте операнда |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Скрыть нижний индекс |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Скрыть верхний индекс |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | Место расположения пределов (нижний индекс и верхний индекс) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Символ N-арного оператора, например: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Указывает аргумент нижнего индекса, который, например, в случае интеграла устанавливает нижний предел |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Указывает аргумент верхнего индекса, который, например, в случае интеграла устанавливает верхний предел |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцент (символ в верхней части этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Оборачивает элемент математики в скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Оборачивает элемент математики в указанные символы, такие как скобки или другие символы в качестве обрамления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Размещает этот элемент в группе, используя символ для группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту в верхней части этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Принимает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Принимает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает нижний индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает нижний индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний и верхний индексы слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний и верхний индексы слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний и верхний индексы справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний и верхний индексы справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Принимает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Принимает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Размещает этот элемент в рамочной коробке |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Размещает этот элемент в рамочной коробке |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Размещает этот элемент в не визуальной коробке (логической группировке), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппированным таким образом, чтобы не допускать разрывов строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Размещает в вертикальном массиве |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту в нижней части этого элемента |

### Примеры

Пример:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Также смотрите

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathNaryOperator](../imathnaryoperator)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->