---
title: IMathElement
second_title: Aspose.Sildes для .NET API Reference
description: Базовый интерфейс любого математического элемента дробь, математический текст, функция, выражение с несколькими элементами и т.д.
type: docs
weight: 7980
url: /ru/aspose.slides.mathtext/imathelement/
---

## Интерфейс IMathElement

Базовый интерфейс любого математического элемента: дробь, математический текст, функция, выражение с несколькими элементами и т.д.

```csharp
public interface IMathElement
```

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Устанавливает знак акцента (символ над этим элементом) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Заключает математический элемент в скобки |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Заключает этот элемент в указанные символы, такие как скобки или другие символы как рамка |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя группирующий символ, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Устанавливает линию над этим элементом |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Указывает математический корень заданной степени от указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Принимает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Принимает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Создает подстрочный индекс |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Создает подстрочный индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Создает подстрочный и надстрочный индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Создает надстрочный индекс |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Создает надстрочный индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Принимает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Принимает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Помещает этот элемент в рамку |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Помещает этот элемент в невизуальную коробку (логическую группировку), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Запакованный объект может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован таким образом, чтобы не допускать разрывы строки внутри. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Помещает в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Устанавливает линию под этим элементом |

### Примеры

Пример:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### См. также

* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->