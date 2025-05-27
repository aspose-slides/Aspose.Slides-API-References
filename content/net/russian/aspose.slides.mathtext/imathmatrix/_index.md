---
title: IMathMatrix
second_title: Aspose.Sildes для .NET API Справочник
description: Указывает объект Матрица, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Для размещения матрицы в скобках следует использовать объект разделителя IMathDelimiter. Нулевые аргументы могут использоваться для создания пробелов в матрицах.
type: docs
weight: 8090
url: /ru/aspose.slides.mathtext/imathmatrix/
---

## Интерфейс IMathMatrix

Указывает объект Матрица, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Для размещения матрицы в скобках следует использовать объект разделителя (IMathDelimiter). Нулевые аргументы могут использоваться для создания пробелов в матрицах.

```csharp
public interface IMathMatrix : IMathElement
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: верх, низ и центр. По умолчанию: Центр |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Количество столбцов в матрице |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Значение горизонтального интервала между столбцами матрицы; Если ColumnGapRule установлено на 3 ("Точно"), то единица измерения интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule установлено на 4 ("Множитель"), то единица измерения интерпретируется как количество увеличений 0,5 em. В других случаях игнорируется. По умолчанию: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Тип горизонтального интервала между столбцами матрицы; Единицы измерения горизонтального интервала могут быть em или пункты (хранятся как твипсы). По умолчанию: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Скрывает заполнитель для пустых элементов матрицы. По умолчанию: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Элементы матрицы |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Минимальная ширина столбца в твипсах (1/20 пункта). Ширина пробела (также называется "Column Gap" или "Gap Width") добавляется к MinColumnWidth для определения общего промежутка между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Количество строк в матрице |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Значение вертикального интервала между строками матрицы; Если RowGapRule установлено на 3 ("Точно"), то единица измерения интерпретируется как твипсы (1/20 пункта). Если RowGapRule установлено на 4 ("Множитель"), то единица измерения интерпретируется как полустроки. По умолчанию: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Тип вертикального интервала между строками матрицы; Единицы измерения вертикального интервала могут быть строками или пунктами (хранятся как твипсы). По умолчанию: SingleSpacingGap (0) |

## Методы

| Название | Описание |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Удаляет указанный столбец |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Удаляет указанную строку |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Получает горизонтальное выравнивание указанного столбца |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Вставляет новый столбец после указанного. Изначально все элементы в новом столбце равны null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Вставляет новый столбец перед указанным. Изначально все элементы в новом столбце равны null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Вставляет новую строку после указанной. Изначально все элементы в новой строке равны null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Вставляет новую строку перед указанной. Изначально все элементы в новой строке равны null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Устанавливает горизонтальное выравнивание указанного столбца |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Устанавливает горизонтальное выравнивание указанных столбцов |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Смотрите также

* интерфейс [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->