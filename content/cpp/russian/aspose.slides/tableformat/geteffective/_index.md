---
title: GetEffective()
second_title: Aspose.Slides для C++ справочник API
description: Получает эффективные свойства форматирования таблицы с учётом наследования и применённых стилей таблицы.
type: docs
weight: 40
url: /ru/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() method


Получает эффективные свойства форматирования таблицы с учётом наследования и применённых стилей таблиц.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Возвращаемое значение

Объект [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Примечания



В этом примере демонстрируется получение эффективного формата заливки для различных логических частей таблицы. Обратите внимание, что форматирование ячейки всегда имеет более высокий приоритет, чем форматирование строки; строка — выше, чем столбец; столбец — выше, чем вся таблица. Поэтому свойства CellFormatEffectiveData в конечном итоге всегда используются для отрисовки таблицы. Следующий код представляет собой лишь пример использования API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Класс [TableFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)