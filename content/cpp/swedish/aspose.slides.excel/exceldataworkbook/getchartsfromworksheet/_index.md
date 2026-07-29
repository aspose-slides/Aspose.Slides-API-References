---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en dictionary som innehåller index och namn på alla diagram i det angivna kalkylbladet i en Excel-arbetsbok.
type: docs
weight: 40
url: /sv/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metod

Hämtar en dictionary som innehåller index och namn på alla diagram i det angivna kalkylbladet i en [Excel](../../) arbetsbok.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som ska sökas efter diagram. |

### Returvärde

En dictionary där nyckeln är diagrammets index och värdet är diagrammets namn.

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [String](../../../system/string/)
* Klass [ExcelDataWorkbook](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)