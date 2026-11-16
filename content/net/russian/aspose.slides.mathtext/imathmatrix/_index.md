---
title: IMathMatrix
second_title: Aspose.Sildes для .NET справочник API
description: Определяет объект Matrix, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы разместить матрицу в скобках, следует использовать объект-разделитель IMathDelimiter. Для создания пробелов в матрицах можно использовать null-аргументы.
type: docs
weight: 8360
url: /ru/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix интерфейс

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Свойства

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom, center. По умолчанию: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Количество столбцов в матрице |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Значение горизонтального интервала между столбцами матрицы; Если ColumnGapRule установлен в 3 ("Exactly"), то единица измеряется в twips (1/20 пункта). Если ColumnGapRule установлен в 4 ("Multiple"), то единица измеряется как количество шагов 0.5 em. В остальных случаях игнорируется. По умолчанию: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Тип горизонтального интервала между столбцами матрицы; Единицы могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Скрыть заполнители для пустых элементов матрицы. По умолчанию: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Элементы матрицы |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Минимальная ширина столбца в twips (1/20 пункта). Промежуток (также именуемый «Column Gap» или «Gap Width») добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Количество строк в матрице |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Значение вертикального интервала между строками матрицы; Если RowGapRule установлен в 3 ("Exactly"), то единица измеряется в twips (1/20 пункта). Если RowGapRule установлен в 4 ("Multiple"), то единица измеряется как половина линии. По умолчанию: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Тип вертикального интервала между строками матрицы; Единицы могут быть lines или points (хранятся как twips). По умолчанию: SingleSpacingGap (0) |

## Методы

| Name | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Удаляет указанный столбец |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Удаляет указанную строку |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Получить горизонтальное выравнивание указанного столбца |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Вставить новый столбец после указанного. Изначально все элементы нового столбца имеют значение null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Вставить новый столбец перед указанным. Изначально все элементы нового столбца имеют значение null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Вставить новую строку после указанной. Изначально все элементы новой строки имеют значение null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Вставить новую строку перед указанной. Изначально все элементы новой строки имеют значение null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Установить горизонтальное выравнивание указанного столбца |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Установить горизонтальное выравнивание указанных столбцов |

### Примеры

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Смотрите также

* интерфейс [IMathElement](../imathelement)
* пространство имён [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->