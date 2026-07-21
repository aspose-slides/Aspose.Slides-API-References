---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные свойства форматирования столбцов таблицы с учётом наследования и применённых стилей таблицы.
type: docs
weight: 1
url: /ru/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() метод


Получает эффективные свойства форматирования столбцов таблицы с учётом наследования и применённых стилей таблицы.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Возвращаемое значение

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Примечания



Этот пример демонстрирует получение эффективного формата заливки для различных логических частей таблицы. Обратите внимание, что форматирование ячейки всегда имеет более высокий приоритет, чем форматирование строки, строка — выше, чем столбец, столбец — выше, чем вся таблица. Поэтому свойства CellFormatEffectiveData в конце всегда используются для отрисовки таблицы. Последующий код является лишь примером использования API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Вывод и сравнение
```

## Смотрите также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Класс [ColumnFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)