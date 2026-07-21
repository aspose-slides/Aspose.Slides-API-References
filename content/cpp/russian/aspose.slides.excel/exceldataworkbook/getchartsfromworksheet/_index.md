---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides для C++ справочное руководство API
description: Возвращает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги Excel.
type: docs
weight: 40
url: /ru/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) метод

Возвращает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа, в котором следует искать диаграммы. |

### Возвращаемое значение

Словарь, где ключ — индекс диаграммы, а значение — имя диаграммы.

## Примечания



Пример: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [String](../../../system/string/)
* Класс [ExcelDataWorkbook](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)