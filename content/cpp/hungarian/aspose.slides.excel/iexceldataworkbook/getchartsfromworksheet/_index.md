---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API Referenciája
description: Lekér egy szótárat, amely a megadott munkalapon található összes diagram indexeit és neveit tartalmaz egy Excel munkafüzetben.
type: docs
weight: 27
url: /hu/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metódus


Lekér egy szótárat, amely a megadott munkalapon található összes diagram indexeit és neveit tartalmaz egy [Excel](../../) munkafüzetben.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve, amelyen a diagramokat keresni kell. |

### Visszatérési érték

Egy szótár, amelyben a kulcs a diagram indexe, az érték pedig a diagram neve.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)