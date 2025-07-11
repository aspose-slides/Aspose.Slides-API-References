---
title: GetEffective
second_title: Aspose.Sildes для .NET API Справочник
description: Получает эффективные свойства форматирования строки таблицы с применением наследования и стилей таблицы.
type: docs
weight: 10
url: /ru/aspose.slides/rowformat/geteffective/
---

## RowFormat.GetEffective метод

Получает эффективные свойства форматирования строки таблицы с применением наследования и стилей таблицы.

```csharp
public IRowFormatEffectiveData GetEffective()
```

### Значение возвращаемого параметра

[`IRowFormatEffectiveData`](../../irowformateffectivedata).

### Примеры

Этот пример демонстрирует получение эффективного формата заполнения для различных частей логики таблицы. Обратите внимание, что форматирование ячеек всегда имеет более высокий приоритет, чем форматирование строки, форматирование строки - выше, чем форматирование столбца, а форматирование столбца - выше, чем форматирование всей таблицы. Таким образом, свойства CellFormatEffectiveData всегда используются для отрисовки таблицы. Следующий код является всего лишь примером API.

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

* интерфейс [IRowFormatEffectiveData](../../irowformateffectivedata)
* класс [RowFormat](../../rowformat)
* пространство имен [Aspose.Slides](../../rowformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->