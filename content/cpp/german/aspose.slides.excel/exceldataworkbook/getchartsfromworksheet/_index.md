---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein Wörterbuch ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer Excel-Arbeitsmappe enthält.
type: docs
weight: 40
url: /de/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) Methode


Ruft ein Wörterbuch ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer [Excel](../../) Arbeitsmappe enthält.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, in dem nach Diagrammen gesucht werden soll. |

### Rückgabewert

Ein Wörterbuch, wobei der Schlüssel der Diagramm-Index und der Wert der Diagramm-Name ist.
## Bemerkungen



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
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelDataWorkbook](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)