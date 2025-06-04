---
title: MathMatrix
second_title: Aspose.Sildes для .NET API Reference
description: Указывает объект Matrix, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект разделителя IMathDelimiter. Нулевые аргументы могут быть использованы для создания пробелов в матрицах.
type: docs
weight: 8590
url: /ru/aspose.slides.mathtext/mathmatrix/
---

## Класс MathMatrix

Указывает объект Matrix, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект разделителя (IMathDelimiter). Нулевые аргументы могут быть использованы для создания пробелов в матрицах.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Инициализирует новый экземпляр класса MathMatrix. |

## Свойства

| Название | Описание |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Количество столбцов в матрице |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлено на 3 ("Точно"), то единица интерпретируется как twips (1/20 от пункта). Если ColumnGapRule установлено на 4 ("Множитель"), то единица интерпретируется как количество увеличений 0.5 em. В других случаях игнорируется. По умолчанию: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Тип горизонтального расстояния между столбцами матрицы; Единицы горизонтального расстояния могут быть em или пункты (хранятся как twips). По умолчанию: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Скрывает заполнитель для пустых элементов матрицы. По умолчанию: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Элемент матрицы |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Минимальная ширина столбца в twips (1/20 от пункта). Расстояние (также называемое "Ширина пробела" или "Column Gap") добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Количество строк в матрице |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Значение вертикального расстояния между строками матрицы; Если RowGapRule установлено на 3 ("Точно"), то единица интерпретируется как twips (1/20 от пункта). Если RowGapRule установлено на 4 ("Множитель"), то единица интерпретируется как половинные строки. По умолчанию: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Тип вертикального расстояния между строками матрицы; Единицы вертикального расстояния могут быть строками или пунктами (хранятся как twips). По умолчанию: SingleSpacingGap (0) |

## Методы

| Название | Описание |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Устанавливает акцентный знак (символ сверху этого элемента) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Принимает заданную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Принимает заданную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Принимает заданную функцию, используя этот экземпляр в качестве аргумента |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Принимает заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Принимает заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Удаляет указанный столбец |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Удаляет указанную строку |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Создает дробь с этим числителем и заданным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Создает дробь с этим числителем и заданным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Создает дробь заданного типа с этим числителем и заданным знаменателем |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Создает дробь заданного типа с этим числителем и заданным знаменателем |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Ограничивает математический элемент в скобках |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Ограничивает математический элемент в указанных символах, таких как скобки или другие символы в качестве рамки |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Принимает функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Принимает функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Получить дочерние элементы |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Получить горизонтальное выравнивание указанного столбца |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Вставляет новый столбец после указанного. Изначально все элементы в новом столбце равны null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Вставляет новый столбец перед указанным. Изначально все элементы в новом столбце равны null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Вставляет новую строку после указанной. Изначально все элементы в новой строке равны null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Вставляет новую строку перед указанной. Изначально все элементы в новой строке равны null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Принимает интеграл без пределов |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Принимает интеграл |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Принимает интеграл |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Соединяет математический элемент и формирует математический блок |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Соединяет математический текст и формирует математический блок |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Создает N-арный оператор |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Создает N-арный оператор |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Устанавливает черту на вершине этого элемента |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Указывает математический корень заданной степени от указанного аргумента. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Указывает математический корень заданной степени от указанного аргумента. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Устанавливает горизонтальное выравнивание указанного столбца |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Устанавливает горизонтальное выравнивание указанных столбцов |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Устанавливает нижний предел |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Устанавливает нижний предел |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Создает подстрочный индекс |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Создает подстрочный индекс |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Создает подстрочный и надстрочный индекс слева |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Создает подстрочный и надстрочный индекс справа |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Создает подстрочный и надстрочный индекс справа |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Создает надстрочный индекс |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Создает надстрочный индекс |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Устанавливает верхний предел |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Устанавливает верхний предел |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Размещает этот элемент в границах |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Размещает этот элемент в границах |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Размещает этот элемент в невизуальной коробке (логGrouping), которая используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппирован таким образом, чтобы не разрешать разрывы строк внутри. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Размещает в вертикальном массиве |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Устанавливает черту внизу этого элемента |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### См. также

* класс [MathElementBase](../mathelementbase)
* интерфейс [IMathMatrix](../imathmatrix)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
