---
title: GetEffective()
second_title: Aspose.Slides для справочника API C++
description: Получает эффективные свойства форматирования строк таблицы с учётом наследования и применённых стилей таблицы.
type: docs
weight: 1
url: /ru/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() метод

Получает эффективные свойства форматирования строк таблицы с учётом наследования и применённых стилей таблицы.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### Возвращаемое значение

Объект [IRowFormatEffectiveData](../../irowformateffectivedata/).

## Примечания

Этот пример демонстрирует получение эффективного формата заливки для разных логических частей таблицы. Обратите внимание, что форматирование ячейки всегда имеет более высокий приоритет, чем форматирование строки, строка — выше, чем столбец, столбец — выше, чем вся таблица. Поэтому в конечном итоге свойства CellFormatEffectiveData всегда используются для отрисовки таблицы. Следующий код является лишь примером использования API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Вывод и сравнение
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Класс [RowFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)