---
title: MathArray
second_title: Aspose.Sildes для .NET API Reference
description: Указывает вертикальный массив уравнений или любых математических объектов
type: docs
weight: 8290
url: /ru/aspose.slides.mathtext/matharray/
---

## MathArray class

Указывает вертикальный массив уравнений или любых математических объектов

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## Конструкторы

| Name | Description |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Создает математический массив и помещает в него указанные элементы |
| [MathArray](matharray#constructor)(IMathElement) | Создает математический массив и помещает в него указанный элемент |

## Свойства

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | Набор элементов массива |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Указывает выравнивание массива относительно окружающего текста. Текст вне массива может быть выровнен по нижней, верхней или центральной части объекта массива. Значение по умолчанию: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Максимальное распределение. Если true, массив растягивается до максимальной ширины содержащего элемента (страницы, колонки, ячейки и т.д.). |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Распределение объектов. Если true, содержимое массива распределяется по максимальной ширине объекта массива. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Интервал между строками массива. Используется только тогда, когда RowSpacingRule установлено в 3 Exactly, в этом случае единицей измерения являются пункты или Multiple, в этом случае единицей измерения являются половинные строки. Значение по умолчанию: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | Тип вертикального интервала между элементами массива. Значение по умолчанию: SingleLineGap |

## Методы

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцент (символ над элементом) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Берет указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Берет указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Берет указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Берет указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Берет указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Заключает математический элемент в скобки |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Заключает математический элемент в указанные символы, такие как скобки или другие символы в качестве обрамления |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Берет функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Берет функцию аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Делает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Делает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Делает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Делает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Делает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени из указанного аргумента. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Указывает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Указывает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает нижний индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает нижний индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний индекс и верхний индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний индекс и верхний индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний индекс и верхний индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Указывает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Указывает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в границу |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в границу |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группировка), которая используется для группировки компонентов уравнения или другого примера математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или группироваться так, чтобы не допускать разрывов строки внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту под этим элементом |

### Примеры

Пример:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### Смотрите также

* class [MathElementBase](../mathelementbase)
* interface [IMathArray](../imatharray)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->