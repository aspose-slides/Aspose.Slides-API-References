---
title: MathBlock
second_title: Справочник API Aspose.Sildes для .NET
description: Определяет экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представляются как математический блок.
type: docs
weight: 8590
url: /ru/aspose.slides.mathtext/mathblock/
---
## MathBlock класс

Определяет экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представляются в виде математического блока.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Инициализирует новый экземпляр класса MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Создает новый математический блок и помещает в него указанные элементы |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Создает новый математический блок и помещает в него указанный элемент |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Получает количество дочерних математических элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Возвращает false, так как коллекцию дочерних элементов можно изменять. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Получает или задает IMathElement по указанному индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцентный знак (символ над этим элементом) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Добавляет математический элемент в конец коллекции. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Применяет указанную функцию, используя этот экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Применяет указанную функцию, используя этот экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Применяет указанную функцию, используя этот экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Применяет указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Применяет указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Удаляет все элементы из коллекции. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Определяет, содержит ли коллекция указанное значение. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Копирует в указанный массив. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Разделяет дочерние элементы символом-разделителем (без скобок). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Заключает математический элемент в скобки. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, и разделяет их символом-разделителем. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Применяет функцию аргумента, используя этот экземпляр в качестве имени функции. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Применяет функцию аргумента, используя этот экземпляр в качестве имени функции. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Получает дочерние элементы. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Размещает этот элемент в группе, используя фигурную скобку снизу. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Размещает этот элемент в группе, используя символ группировки, например, фигурную скобку снизу или другой. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Определяет индекс конкретного математического элемента в коллекции. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Вставляет MathElement в коллекцию по указанному индексу. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Вычисляет интеграл без пределов. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Вычисляет интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Вычисляет интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Вычисляет интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Вычисляет интеграл. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Объединяет математический элемент с этим математическим блоком. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Объединяет математический текст с этим блоком. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Объединяет другой математический блок с текущим. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMMathElement, IMathElement) | Создает N-арный оператор. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Задает математический корень заданной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Задает математический корень заданной степени из указанного аргумента. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Удаляет первое вхождение указанного объекта из коллекции. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Удаляет элемент по указанному индексу в коллекции. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Получает нижний предел. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Получает нижний предел. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает нижний индекс. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает нижний индекс. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает нижний и верхний индексы справа. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает нижний и верхний индексы справа. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает верхний индекс. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает верхний индекс. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Получает верхний предел. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Получает верхний предел. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Размещает элемент в рамке. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Размещает элемент в рамке. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Размещает элемент в невизуальном контейнере (логической группе), используемом для группировки компонентов уравнения или другого фрагмента математического текста. Такой контейнер может, например, выступать в роли эмулятора оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппирован так, чтобы внутри не допускать разрывов строк. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Размещает дочерние элементы в вертикальном массиве. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту под этим элементом. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Сохраняет содержимое этого [`MathBlock`](../mathblock) в формате MathML. |

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### См. также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathBlock](../imathblock)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->