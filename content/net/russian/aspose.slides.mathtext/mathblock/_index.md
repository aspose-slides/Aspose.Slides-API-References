---
title: MathBlock
second_title: Aspose.Sildes для .NET: справочник API
description: Определяет экземпляр математического текста, содержащегося в MathParagraph и начинающегося с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены в виде math block.
type: docs
weight: 8610
url: /ru/aspose.slides.mathtext/mathblock/
---
## MathBlock класс

Определяет экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки. Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены в виде math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Инициализирует новый экземпляр класса MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Создаёт новый математический блок и помещает в него указанные элементы. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Создаёт новый математический блок и помещает в него указанный элемент. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Возвращает количество дочерних математических элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Возвращает false, потому что коллекцию дочерних элементов можно изменять. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Получает или задает IMathElement по указанному индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает знак ударения (символ над этим элементом). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Добавляет математический элемент в конец коллекции. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Выполняет указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Выполняет указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Выполняет указанную функцию, используя данный экземпляр в качестве аргумента. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Выполняет указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Выполняет указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Удаляет все элементы из коллекции. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Определяет, содержит ли коллекция указанное значение. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Копирует в указанный массив. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Разделяет дочерние элементы заданным символом-разделителем (без скобок). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создаёт дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создаёт дробь с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Заключает математический элемент в скобки. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы, в качестве рамки. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Оборачивает дочерние элементы этого блока в указанные символы (например, скобки) и разделяет их символом-разделителем. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Выполняет функцию аргумента, используя данный экземпляр в качестве имени функции. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Выполняет функцию аргумента, используя данный экземпляр в качестве имени функции. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Получает дочерние элементы. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Группирует этот элемент, используя нижнюю фигурную скобку. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Группирует этот элемент, используя символ группировки, например нижнюю фигурную скобку или иной. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Определяет индекс конкретного математического элемента в коллекции. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Вставляет MathElement в коллекцию по указанному индексу. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Создаёт интеграл без пределов. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Создаёт интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Создаёт интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Создаёт интеграл. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Создаёт интеграл. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Присоединяет математический элемент к этому блоку. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Присоединяет математический текст к этому блоку. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Присоединяет другой математический блок к текущему. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создаёт N-арный оператор. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создаёт N-арный оператор. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту над этим элементом. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Задает корень заданной степени из указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Задает корень заданной степени из указанного аргумента. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Удаляет первое вхождение указанного объекта из коллекции. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Создаёт нижний предел. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Создаёт нижний предел. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создаёт нижний индекс. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создаёт нижний индекс. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создаёт нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создаёт нижний и верхний индексы слева. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создаёт нижний и верхний индексы справа. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создаёт нижний и верхний индексы справа. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создаёт верхний индекс. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создаёт верхний индекс. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Создаёт верхний предел. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Создаёт верхний предел. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Помещает этот элемент в рамочный блок. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Помещает этот элемент в рамочный блок. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Помещает этот элемент в невизуальный блок (логическая группировка), используемый для объединения компонентов уравнения или другого математического текста. Такой объект может служить, например, эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или группироваться так, чтобы запрещать разрывы внутри. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Размещает дочерние элементы в вертикальном массиве. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту внизу этого элемента. |
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
* пространство имён [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->