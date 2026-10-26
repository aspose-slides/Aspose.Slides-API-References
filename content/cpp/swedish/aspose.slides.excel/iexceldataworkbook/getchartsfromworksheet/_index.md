---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en ordbok som innehåller index och namn på alla diagram i det angivna kalkylbladet i en Excel-arbetsbok.
type: docs
weight: 27
url: /sv/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metod


Hämtar en ordbok som innehåller index och namn på alla diagram i det angivna kalkylbladet i en [Excel](../../) arbetsbok.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som ska sökas efter diagram. |

### Returvärde

En ordbok där nyckeln är diagramindexet och värdet är diagramnamnet.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [String](../../../system/string/)
* Klass [IExcelDataWorkbook](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)