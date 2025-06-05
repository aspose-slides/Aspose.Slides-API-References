---
title: MathDelimiter
second_title: Aspose.Sildes для .NET API Reference
description: Указывает объект разделителя, состоящий из открывающих и закрывающих символов, таких как скобки, фигурные скобки, квадратные скобки и вертикальные линии, и одного или нескольких математических элементов внутри, разделенных указанным символом. Примеры 2 2x7C2
type: docs
weight: 8390
url: /ru/aspose.slides.mathtext/mathdelimiter/
---

## MathDelimiter class

Указывает объект разделителя, состоящий из открывающих и закрывающих символов (таких как скобки, фигурные скобки, квадратные скобки и вертикальные линии), и одного или нескольких математических элементов внутри, разделенных указанным символом. Примеры: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Constructors

| Name | Description |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Инициализирует MathDelimiter с указанным элементом в качестве единственного базового аргумента |

## Properties

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Один или несколько математических элементов, разделенных символами-разделителями |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Символ начала разделителя указывает на начальный или открывающий символ разделителя. Математические разделители — это заключающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Указывает форму разделителей в объекте разделителя. Когда это MathDelimiterShape.Centered, разделители центрируются вокруг математической оси математического текста и могут быть сделаны так, чтобы соответствовать всей высоте их содержимого. Когда это MathDelimiterShape.Match, их высота и форма изменяются так, чтобы точно соответствовать их содержимому. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Символ конца разделителя указывает на конечный или закрывающий символ разделителя. Математические разделители — это заключающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Указывает на рост символа начала, символа-разделителя, символа конца. Когда установлено в true, разделители растут вертикально, чтобы соответствовать высоте своего операнда. Значение по умолчанию — true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Символ разделителя указывает на символ, который разделяет аргументы в объекте разделителя. По умолчанию: '&#x7C;'. |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает знак акцента (символ в верхней части этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Разделяет аргументы с использованием указанного символа разделителя |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Оборачивает математический элемент в скобки |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Оборачивает математический элемент в указанные символы, такие как скобки или другие символы в качестве обрамления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает бар на верхней части этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени из указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Принимает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Принимает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает нижний индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает нижний индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний индекс и верхний индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Принимает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Принимает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамку |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группировка), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппированным так, чтобы не позволять разрывы строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает бар внизу этого элемента |

### Examples

Пример:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->