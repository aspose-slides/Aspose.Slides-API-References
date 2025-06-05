---
title: MathElementBase
second_title: Aspose.Sildes для .NET API Справка
description: Базовый класс для IMathElement с реализацией некоторых методов, которые общие для всех наследуемых классов. Только для внутреннего использования. Наследуемый класс должен быть IMathElement.
type: docs
weight: 8420
url: /ru/aspose.slides.mathtext/mathelementbase/
---

## Класс MathElementBase

Базовый класс для IMathElement с реализацией некоторых методов, которые общие для всех наследуемых классов. Только для внутреннего использования. Наследуемый класс должен быть IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцентный знак (символ сверху этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Использует указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Использует указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Использует указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Использует указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Использует указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Обрамляет математический элемент в скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Обрамляет математический элемент в указанные символы, такие как скобки или другие символы для оформления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Использует функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Использует функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Указывает математический корень данного степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Указывает математический корень данного степени из указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Указывает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Указывает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Создает нижний индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Создает нижний индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Создает нижний индекс и верхний индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Создает верхний индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Создает верхний индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Указывает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Указывает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Помещает этот элемент в рамку |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группировка), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить в качестве точки разрыва строки или быть сгруппирован так, чтобы не допускать разрыва строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Размещает в вертикальном массиве |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту под этим элементом |

### Смотрите также

* интерфейс [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->