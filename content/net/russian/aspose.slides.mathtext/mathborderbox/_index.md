---
title: MathBorderBox
second_title: Aspose.Sildes для .NET API Справочник
description: Рисует прямоугольную или другую рамку вокруг IMathElement.
type: docs
weight: 8350
url: /ru/aspose.slides.mathtext/mathborderbox/
---

## Класс MathBorderBox

Рисует прямоугольную или другую рамку вокруг IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Создает элемент MathBorderBox с прямоугольной рамкой |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Создает элемент MathBorderBox |

## Свойства

| Название | Описание |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Базовый аргумент |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Скрыть нижний край (по умолчанию false) - указывает состояние видимости нижнего края рамки. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Скрыть левый край (по умолчанию false) - указывает состояние видимости левого края рамки. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Скрыть правый край (по умолчанию false) - указывает состояние видимости правого края рамки. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Скрыть верхний край (по умолчанию false) - указывает состояние видимости верхнего края рамки. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Зачеркивание снизу слева до верху справа (по умолчанию false). Указывает состояние видимости зачеркивающей диагональной линии от нижнего левого угла до верхнего правого угла рамки. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Зачеркивание по горизонтали (по умолчанию false) - указывает состояние видимости зачеркивающей горизонтальной линии. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Зачеркивание сверху слева до снизу справа (по умолчанию false). Указывает состояние видимости зачеркивающей диагональной линии от верхнего левого угла до нижнего правого угла рамки. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Зачеркивание по вертикали (по умолчанию false) - указывает состояние видимости зачеркивающей вертикальной линии. |

## Методы

| Название | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцент (символ над этим элементом) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Заключает математический элемент в скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Заключает математический элемент в указанные символы, такие как скобки или другие символы в качестве обрамления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Берет интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Берет интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Берет интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает линию над этим элементом |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Указывает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Указывает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает подстрочный индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает подстрочный индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает подстрочный и надстрочный индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает надстрочный индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает надстрочный индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Указывает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Указывает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Размещает этот элемент в рамке |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Размещает этот элемент в рамке |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Размещает этот элемент в невизуальной коробке (логической группировке), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объединенный объект может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или группироваться так, чтобы не допускать разрывов строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Размещает в вертикальном массиве |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает линию под этим элементом |

### Примеры

Пример:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### См. также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathBorderBox](../imathborderbox)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->