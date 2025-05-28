---  
title: MathArray  
second_title: Aspose.Sildes для .NET API Справочник  
description: Определяет вертикальный массив уравнений или любых математических объектов
type: docs  
weight: 8290  
url: /ru/aspose.slides.mathtext/matharray/
---  

## Класс MathArray  

Определяет вертикальный массив уравнений или любых математических объектов  

```csharp  
public sealed class MathArray : MathElementBase, IMathArray  
```  

## Конструкторы  

| Имя | Описание |  
| --- | --- |  
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Создает математический массив и помещает в него указанные элементы |  
| [MathArray](matharray#constructor)(IMathElement) | Создает математический массив и помещает в него указанный элемент |  

## Свойства  

| Имя | Описание |  
| --- | --- |  
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | Набор элементов массива |  
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Указывает выравнивание массива относительно окружающего текста. Текст вне массива может быть выровнен по нижнему, верхнему или центру объекта массива. Значение по умолчанию: Центр |  
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Максимальное распределение. Когда истинно, массив распределяется на максимальную ширину содержащего элемента (страница, колонка, ячейка и т.д.). |  
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Распределение объекта. Когда истинно, содержимое массива распределяется на максимальную ширину объекта массива. |  
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Интервал между строками массива. Используется только когда RowSpacingRule установлен на 3 Exactly, в этом случае единица измерения - пункты или Multiple, в этом случае единица измерения - половинные линии. Значение по умолчанию: 0 |  
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | Тип вертикального интервала между элементами массива. Значение по умолчанию: SingleLineGap |  

## Методы  

| Имя | Описание |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцентный знак (символ над этим элементом) |  
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
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Заключает математический элемент в указанные символы, такие как скобки или другие символы для обрамления |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |  
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Получает дочерние элементы |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу, используя нижнюю фигурную скобку |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Объединяет математический элемент и образует математический блок |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Объединяет математический текст и образует математический блок |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |  
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Устанавливает нижний предел |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Устанавливает нижний предел |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает нижний индекс |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает нижний индекс |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний и верхний индексы слева |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний и верхний индексы слева |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний и верхний индексы справа |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний и верхний индексы справа |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Устанавливает верхний предел |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Устанавливает верхний предел |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамку |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамку |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группа), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой переноса строки или быть сгруппирован, чтобы не допустить разрывов строк внутри. |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту под этим элементом |  

### Примеры  

Пример:  

```csharp  
[C#]  
MathArray mathArray = new MathArray(new MathematicalText("item1"));  
```  

### См. также  

* класс [MathElementBase](../mathelementbase)  
* интерфейс [IMathArray](../imatharray)  
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* сборка [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  