---  
title: MathSuperscriptElement
second_title: Aspose.Sildes for .NET API Reference  
description: Указывает объект надстрочного текста, который состоит из основания и уменьшенного надстрочного текста, расположенного выше и справа
type: docs
weight: 8750  
url: /ru/aspose.slides.mathtext/mathsuperscriptelement/
---  
  
## MathSuperscriptElement class  
  
Указывает объект надстрочного текста, который состоит из основания и уменьшенного надстрочного текста, расположенного выше и справа  
  
```csharp  
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement  
```  
  
## Constructors  
  
| Name | Description |  
| --- | --- |  
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | Инициализирует новый экземпляр класса MathSuperscriptElement. |  
  
## Properties  
  
| Name | Description |  
| --- | --- |  
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Аргумент основания |  
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | Надстрочный текст |  
  
## Methods  
  
| Name | Description |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцент (символ сверху этого элемента) |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Берет заданную функцию, используя этот экземпляр в качестве аргумента |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Берет заданную функцию, используя этот экземпляр в качестве аргумента |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Берет заданную функцию, используя этот экземпляр в качестве аргумента |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Берет заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Берет заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и заданным знаменателем |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и заданным знаменателем |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь заданного типа с этим числителем и заданным знаменателем |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь заданного типа с этим числителем и заданным знаменателем |  
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Обрамляет математический элемент в скобки |  
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Обрамляет математический элемент в указанные символы, такие как скобки или другие символы для оформления |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Берет функцию аргумента, используя этот экземпляр в качестве имени функции |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Берет функцию аргумента, используя этот экземпляр в качестве имени функции |  
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | Получить дочерние элементы |  
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
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает линию сверху этого элемента |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Указывает нижний предел |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Указывает нижний предел |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает индексированный текст |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает индексированный текст |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает индексированный текст и надстрочный текст слева |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает индексированный текст и надстрочный текст слева |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает индексированный текст и надстрочный текст справа |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает индексированный текст и надстрочный текст справа |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает надстрочный текст |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает надстрочный текст |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Указывает верхний предел |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Указывает верхний предел |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Размещает этот элемент в рамке |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Размещает этот элемент в рамке |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Размещает этот элемент в невизуальной коробке (логическая группировка), которая используется для группировки компонентов уравнения или другого примера математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован таким образом, чтобы не допустить разрывов строк внутри. |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Помещает в вертикальный массив |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает линию снизу этого элемента |  
  
### Examples  
  
Пример:  
  
```csharp  
[C#]  
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");  
```  
  
### See Also  
  
* class [BaseScript](../basescript)  
* interface [IMathSuperscriptElement](../imathsuperscriptelement)  
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* assembly [Aspose.Slides](../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  