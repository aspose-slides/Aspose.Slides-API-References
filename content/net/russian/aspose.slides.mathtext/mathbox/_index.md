---
title: MathBox
second_title: Aspose.Sildes для .NET API Reference
description: Указывает логическую упаковку математического элемента. Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть группированным так, чтобы не допускать разрывов строк внутри. Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строк.
type: docs
weight: 8370
url: /ru/aspose.slides.mathtext/mathbox/
---

## MathBox класс

Указывает логическую упаковку (упаковку) математического элемента. Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть группированным так, чтобы не допускать разрывов строк внутри. Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строк.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Инициализирует MathBox с указанным элементом в качестве аргумента |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Когда true, этот эмулятор оператора служит точкой выравнивания; то есть, назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Базовый аргумент |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Дифференциал. Когда true, коробка ведет себя как дифференциал (например, 𝑑𝑥 в интеграле) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Явный разрыв указывает, существует ли разрыв строки в начале объекта Box, так что строка оборачивается в начале объекта box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (без явного разрыва) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Без разрыва. Это свойство указывает "неразрывное" свойство на объекте box. Когда true, разрывы строк в рамках коробки не могут происходить. Это может быть важно для эмуляторов операторов, которые состоят из более чем одного бинарного оператора. Когда этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Эмулятор оператора. Когда true, коробка и ее содержимое ведут себя как единый оператор и наследуют свойства оператора. Это значит, что, например, символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов объединяются, чтобы образовать оператор, такой как '=='. Значение по умолчанию: false |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцент (символ на верхней части этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Берет указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Берет указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Берет указанную функцию, используя этот экземпляр как аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Берет указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Берет указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Оборачивает элемент математики в скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Оборачивает элемент математики в указанные символы, такие как скобки или другие символы в качестве рамки |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Берет функцию аргумента, используя этот экземпляр как имя функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Берет функцию аргумента, используя этот экземпляр как имя функции |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Получить дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу с использованием нижней фигурной скобки |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу с использованием символа группировки, такого как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Берет интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Берет интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет элемент математики и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту на верхней части этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени из указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Берет нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Берет нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает подстрочный индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает подстрочный индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индексы слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает подстрочный и надстрочный индексы слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индексы справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает подстрочный и надстрочный индексы справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает надстрочный индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает надстрочный индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Берет верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Берет верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамку |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группировка), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Упакованный объект может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывы строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту на нижней части этого элемента |

### Примеры

Пример:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### См. также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathBox](../imathbox)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->