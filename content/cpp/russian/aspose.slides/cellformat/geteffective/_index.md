---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные свойства форматирования ячеек таблицы с учётом наследования и применённых стилей таблицы.
type: docs
weight: 118
url: /ru/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() метод

Получает эффективные свойства форматирования ячеек таблицы с учётом наследования и применённых стилей таблицы.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Возвращаемое значение

Объект [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Примечания

Этот пример демонстрирует получение эффективного формата заливки для различных логических частей таблицы. Обратите внимание, что форматирование ячейки всегда имеет более высокий приоритет, чем форматирование строки, строка — выше, чем столбец, столбец — выше, чем вся таблица. Поэтому в конечном итоге свойства CellFormatEffectiveData всегда используются для рисования таблицы. Ниже приведён код, представляющий лишь пример использования API. 
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Класс [CellFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)