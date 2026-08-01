---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal een woordenboek op dat de indexen en namen van alle grafieken in het opgegeven werkblad van een Excel-werkmap bevat.
type: docs
weight: 40
url: /nl/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) methode

Haal een woordenboek op dat de indexen en namen van alle grafieken in het opgegeven werkblad van een [Excel](../../) werkmap bevat.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad waarin gezocht moet worden naar grafieken. |

### Retourwaarde

Een woordenboek waarbij de sleutel de grafiekindex is en de waarde de grafieknaam.

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelDataWorkbook](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)