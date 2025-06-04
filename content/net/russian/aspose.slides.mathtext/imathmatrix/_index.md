---
title: IMathMatrix
second_title: Aspose.Slides для .NET API Справочник
description: Указывает на объект Matrix, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, вы должны использовать объект разделителя IMathDelimiter. Для создания пробелов в матрицах можно использовать нулевые аргументы.
type: docs
weight: 8090
url: /ru/aspose.slides.mathtext/imathmatrix/
---

## Интерфейс IMathMatrix

Указывает на объект Matrix, состоящий из дочерних элементов, расположенных в одном или нескольких рядах и столбцах. Важно отметить, что матрицы не имеют встроенных разделителей. Чтобы поместить матрицу в скобки, вы должны использовать объект разделителя (IMathDelimiter). Для создания пробелов в матрицах можно использовать нулевые аргументы.

```csharp
public interface IMathMatrix : IMathElement
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Количество столбцов в матрице |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлено на 3 ("Точно"), то единица интерпретируется как твипсы (1/20 пунктов) Если ColumnGapRule установлено на 4 ("Множественное"), то единица интерпретируется как число увеличений на 0.5 em. В других случаях игнорируется. По умолчанию: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Тип горизонтального расстояния между столбцами матрицы; Единицы горизонтального расстояния могут быть em или точки (сохраняются как твипсы). По умолчанию: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Скрыть заполнитель для пустых элементов матрицы По умолчанию: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Элементы матрицы |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Минимальная ширина столбца в твипсах (1/20 пунктов) Пробел между столбцами (также называемый "Пробел между столбцами" или "Ширина пробела") добавляется к MinColumnWidth, чтобы определить общее расстояние между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Количество рядов в матрице |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Значение вертикального расстояния между рядами матрицы; Если RowGapRule установлено на 3 ("Точно"), то единица интерпретируется как твипсы (1/20 пунктов) Если RowGapRule установлено на 4 ("Множественное"), то единица интерпретируется как половина линий. По умолчанию: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Тип вертикального расстояния между рядами матрицы; Единицы вертикального расстояния могут быть линиями или точками (сохраняются как твипсы). По умолчанию: SingleSpacingGap (0) |

## Методы

| Название | Описание |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Удаляет указанный столбец |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Удаляет указанный ряд |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Получает горизонтальное выравнивание указанного столбца |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Вставляет новый столбец после указанного Изначально все элементы в новом столбце равны null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Вставляет новый столбец перед указанным Изначально все элементы в новом столбце равны null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Вставляет новый ряд после указанного Изначально все элементы в новом ряду равны null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Вставляет новый ряд перед указанным Изначально все элементы в новом ряду равны null. |
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