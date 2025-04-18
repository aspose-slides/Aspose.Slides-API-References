---
title: IMathMatrix
second_title: Справочник по API Aspose.Slides для .NET
description: Задает объект Matrix состоящий из дочерних элементов расположенных в одной или нескольких строках и столбцах. Важно отметить что матрицы не имеют встроенных разделителей. Для помещения матрицы в скобки следует использовать объект-разделитель IMathDelimiter. Нулевые аргументы могут использоваться для создания пробелов в матрицах.
type: docs
weight: 7630
url: /ru/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Задает объект Matrix, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Для помещения матрицы в скобки следует использовать объект-разделитель (IMathDelimiter). Нулевые аргументы могут использоваться для создания пробелов в матрицах.

```csharp
public interface IMathMatrix : IMathElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Задает выравнивание по вертикали относительно окружающего текста. Возможные значения:верх, низ и центр. По умолчанию:Центр |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Количество столбцов в матрице |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Значение горизонтального интервала между столбцами матрицы; Если для ColumnGapRule установлено значение 3 ("Точно"), то единица интерпретируется как твипы (1/20 точки) Если для ColumnGapRule установлено значение 4 ( "Multiple"), то единица измерения интерпретируется как число с шагом 0,5 em. В остальных случаях игнорируется. По умолчанию:0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Тип горизонтального интервала между столбцами матрицы; Единицами интервала по горизонтали могут быть ems или пункты (хранятся как twips). По умолчанию:SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Скрыть заполнители для пустых элементов матрицы По умолчанию:false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Элементы матрицы |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Минимальная ширина столбца в твипах (1/20 пункта) Интервал пробела (также называемый «Разрыв столбца» или «Промежуток Width") добавляется к MinColumnWidth, чтобы определить общее расстояние между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию:0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Количество строк в матрице |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Значение интервала по вертикали между строками матрицы; Если для RowGapRule установлено значение 3 ("Точно"), то единица интерпретируется как твипы (1/20 точки) Если для RowGapRule установлено значение 4 ( «Несколько»), то единица интерпретируется как полулиния. По умолчанию:0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Тип интервала по вертикали между строками матрицы; Единицами интервала по вертикали могут быть линии или точки (хранящиеся как твипы). По умолчанию:SingleSpacingGap (0) |

## Методы

| Имя | Описание |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Удаляет указанный столбец |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Удаляет указанную строку |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Получить горизонтальное выравнивание указанного столбца |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Вставить новый столбец после указанного Изначально все элементы в новом столбце пустые. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Вставить новый столбец перед указанным Изначально все элементы в новом столбце пустые. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Вставить новую строку после указанной Изначально все элементы в новой строке нулевые. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Вставить новую строку перед указанной Изначально все элементы в новой строке нулевые. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Установить горизонтальное выравнивание указанного столбца |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Установить горизонтальное выравнивание указанных столбцов |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Смотрите также

* interface [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
