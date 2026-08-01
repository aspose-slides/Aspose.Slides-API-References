---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt een woordenboek op dat de indexen en namen van alle grafieken in het opgegeven werkblad van een Excel-werkmap bevat.
type: docs
weight: 27
url: /nl/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) methode


Haalt een woordenboek op dat de indexen en namen van alle grafieken in het opgegeven werkblad van een [Excel](../../) werkmap bevat.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad waarin naar grafieken gezocht moet worden. |

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
* Klasse [IExcelDataWorkbook](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)