---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein Wörterbuch ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer Excel-Arbeitsmappe enthält.
type: docs
weight: 27
url: /de/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) Methode

Ruft ein Wörterbuch ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer [Excel](../../) Arbeitsmappe enthält.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, in dem nach Diagrammen gesucht werden soll. |

### Rückgabewert

Ein Wörterbuch, bei dem der Schlüssel der Diagrammindex und der Wert der Diagrammname ist.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)