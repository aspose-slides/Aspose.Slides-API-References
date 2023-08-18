---
title: MathBox
second_title: Справочник по API Aspose.Slides для .NET
description: Задает логическую упаковку упаковку математического элемента. Например объект в штучной упаковке может служить эмулятором оператора с точкой выравнивания или без нее служить точкой разрыва строки или быть сгруппирован чтобы не допускать разрывов строк. в пределах. Например оператор  должен быть помещен в рамку чтобы избежать разрывов строк.
type: docs
weight: 7910
url: /ru/aspose.slides.mathtext/mathbox/
---
## MathBox class

Задает логическую упаковку (упаковку) математического элемента. Например, объект в штучной упаковке может служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть сгруппирован, чтобы не допускать разрывов строк. в пределах. Например, оператор "==" должен быть помещен в рамку, чтобы избежать разрывов строк.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Инициализирует MathBox с указанным элементом в качестве аргумента |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | При значении true этот эмулятор оператора служит точкой выравнивания; то есть, назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию:false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Базовый аргумент |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Дифференциал При значении true блок действует как дифференциал (например, 𝑑𝑥 в подынтегральном выражении) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию:false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, такой, чтобы строка переносилась в начале блока объект. Определяет номер оператора в предыдущей строке математического текста, который должен использоваться в качестве точки выравнивания для текущей строки математического текста возможно значения:1..255 По умолчанию:0 (без явного разрыва) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Без разрыва Это свойство задает свойство "нерушимости" в поле объекта. Если задано значение true, внутри блока не может быть разрывов строк. Это может быть важно для эмуляторов операторов, которые состоят из более чем одного бинарного оператора. Когда этот элемент не указан, внутри блока могут возникать разрывы. По умолчанию:true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Эмулятор оператора. При значении true блок и его содержимое ведут себя как один оператор и наследуют свойства оператора. Это означает, например, что символ может служить точкой для разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов объединяются в оператор, например '=='. Значение по умолчанию:false |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает знак ударения (символ над этим элементом) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Заключает математический элемент в круглые скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Заключает математический элемент в указанные символы, такие как круглые скобки или другие символы в качестве обрамления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Получить дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу с помощью нижней фигурной скобки |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Берет интеграл без ограничений |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Соединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Соединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает полосу в верхней части этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Задает математический корень данной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Задает математический корень данной степени из указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Берет нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Берет нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний и верхний индексы слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний и верхний индексы слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний и верхний индексы справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний и верхний индексы справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Принимает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Принимает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамку |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную рамку (логическая группировка) которая используется для группировки компонентов уравнения или другого экземпляра математического текста . Объект в штучной упаковке может (например) служить эмулятором оператора с точкой выравнивания или без нее, служить точкой разрыва строки или быть сгруппирован, чтобы не допускать ломается внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает полосу внизу этого элемента |

### Примеры

Пример:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Смотрите также

* class [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
