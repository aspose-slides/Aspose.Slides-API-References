---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Vrací slovník obsahující indexy a názvy všech grafů v určeném listu Excel sešitu.
type: docs
weight: 40
url: /cs/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metoda


Vrací slovník obsahující indexy a názvy všech grafů v určeném listu sešitu [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Název listu, ve kterém se mají hledat grafy. |

### Návratová hodnota

Slovník, kde klíč je index grafu a hodnota je název grafu.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDictionary](../../../system.collections.generic/idictionary/)
* Třída [String](../../../system/string/)
* Třída [ExcelDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)