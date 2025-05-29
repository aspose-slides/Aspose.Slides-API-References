---
title: MathBlock
second_title: Aspose.Slides для .NET API Reference
description: Указывает экземпляр математического текста, который содержится в MathParagraph и начинается с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком.
type: docs
weight: 8330
url: /ru/aspose.slides.mathtext/mathblock/
---

## Класс MathBlock

Указывает экземпляр математического текста, который содержится в MathParagraph и начинается с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены математическим блоком.

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
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Получает количество дочерних математических элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Возвращает false, потому что коллекция дочерних элементов может быть изменена. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Получает или задает IMathElement по указанному индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцентный знак (символ сверху этого элемента) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Добавляет математический элемент в конец коллекции. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Удаляет все элементы из коллекции. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Определяет, содержит ли коллекция определенное значение. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Копирует в указанной массив. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Разделяет дочерние элементы с помощью символа-разделителя (без скобок) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Ограничивает математический элемент в скобках |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Ограничивает дочерние элементы этого блока в указанных символах, таких как скобки или другие символы как обрамление |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Ограничивает дочерние элементы этого блока в указанных символах, таких как скобки или другие как обрамление и разделяет с помощью символа-разделителя |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Получает дочерние элементы |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Помещает этот элемент в группу с использованием нижней фигурной скобки |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Определяет индекс определенного математического элемента в коллекции. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Вставляет MathElement в коллекцию по указанному индексу. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Соединяет математический элемент с этим математическим блоком |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Соединяет математический текст с этим математическим блоком |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Соединяет другой математический блок с этим |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту сверху этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Удаляет первое вхождение определенного объекта из коллекции. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Удаляет элемент по указанному индексу в коллекции. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальную коробку (логическая группировка), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован так, чтобы не допускать разрывов строки внутри. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Помещает дочерние элементы в вертикальный массив |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту снизу этого элемента |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Сохраняет содержимое этого [`MathBlock`](../mathblock) как MathML |

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### См. также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathBlock](../imathblock)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->
