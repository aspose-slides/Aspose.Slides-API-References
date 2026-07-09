---
title: MathPhantom
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет фантомный математический объект ltmphantgt, который влияет на расположение дочернего элемента, не обязательно отображая его. Фантом может скрывать базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования места. Видимость и поведение геометрии управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp.
type: docs
weight: 8920
url: /ru/aspose.slides.mathtext/mathphantom/
---
## MathPhantom класс

Представляет собой фантомный математический объект (&lt;m:phant&gt;), который влияет на расположение дочернего элемента, не обязательно отображая его. Фантом может скрывать базовое выражение, сохраняя при этом его ширину, высоту или глубину для выравнивания формул или резервирования места. Видимость и геометрическое поведение управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Создаёт новый экземпляр класса [`MathPhantom`](../mathphantom) с использованием указанного базового математического элемента. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Базовый аргумент |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Получает или задаёт значение, указывающее, отображается ли базовый элемент. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Получает или задаёт значение, указывающее, является ли фантом прозрачным для правил отступов, основанных на классах. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Получает или задаёт значение, указывающее, следует ли считать подъем (высоту над базовой линией) базового элемента равным нулю. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Получает или задаёт значение, указывающее, следует ли считать спуск (глубину ниже базовой линии) базового элемента равным нулю. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Получает или задаёт значение, указывающее, следует ли считать ширину базового элемента равной нулю. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает знак акцента (символ вверху этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создаёт дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создаёт дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Обрамляет математический элемент скобками. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Обрамляет математический элемент указанными символами, такими как скобки или другими символами. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя данный экземпляр в качестве имени функции. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя данный экземпляр в качестве имени функции. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Получает дочерние элементы. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и формирует математический блок. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создаёт N-арный оператор. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создаёт N-арный оператор. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Задаёт математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Задаёт математический корень заданной степени от указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Берёт нижний предел. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Берёт нижний предел. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создаёт нижний индекс. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создаёт нижний индекс. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создаёт нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создаёт нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создаёт нижний и верхний индексы справа. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создаёт нижний и верхний индексы справа. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создаёт верхний индекс. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создаёт верхний индекс. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Берёт верхний предел. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Берёт верхний предел. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамку. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальный блок (логическая группировка), который используется для объединения компонентов уравнения или другого математического текста. Такой блок может, например, выступать в роли эмулятора оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппирован так, чтобы не допускать разрывов строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Размещает в вертикальном массиве. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту под этим элементом. |

### Примеры

Пример:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Скрыть содержимое
phantom.ZeroWidth = false;     // Сохранить ширину
```

### Смотрите также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathPhantom](../imathphantom)
* пространство имён [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->