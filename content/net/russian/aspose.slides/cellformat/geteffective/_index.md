---
title: GetEffective
second_title: Aspose.Slides для .NET API Справочник
description: Получает эффективные свойства форматирования ячеек таблицы с учетом наследования и применяемых стилей таблицы.
type: docs
weight: 90
url: /ru/aspose.slides/cellformat/geteffective/
---

## CellFormat.GetEffective метод

Получает эффективные свойства форматирования ячеек таблицы с учетом наследования и применяемых стилей таблицы.

```csharp
public ICellFormatEffectiveData GetEffective()
```

### Возвращаемое значение

[`ICellFormatEffectiveData`](../../icellformateffectivedata).

### Примеры

Этот пример демонстрирует получение эффективного формата заполнения для различных частей логики таблицы. Обратите внимание, что форматирование ячеек всегда имеет более высокий приоритет, чем форматирование строк, форматирование строк - выше, чем у столбцов, форматирование столбцов - выше, чем у целой таблицы. В итоге свойства CellFormatEffectiveData всегда используются для рисования таблицы. Следующий код является лишь примером API.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    ITable tbl = pres.Slides[0].Shapes[0] as ITable;
    IFillFormatEffectiveData tableFillFormatEffective = tbl.TableFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData rowFillFormatEffective = tbl.Rows[0].RowFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData columnFillFormatEffective = tbl.Columns[0].ColumnFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData cellFillFormatEffective = tbl[0, 0].CellFormat.GetEffective().FillFormat;
    /* Вывод и сравнение */
}
```

### См. также

* интерфейс [ICellFormatEffectiveData](../../icellformateffectivedata)
* класс [CellFormat](../../cellformat)
* пространство имен [Aspose.Slides](../../cellformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->