---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги Excel.
type: docs
weight: 27
url: /ru/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) method


Возвращает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа, в котором ищутся диаграммы. |

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

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [String](../../../system/string/)
* Класс [IExcelDataWorkbook](../)
* Простой имен [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)