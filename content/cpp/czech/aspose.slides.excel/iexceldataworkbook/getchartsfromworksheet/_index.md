---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides pro C++ – reference API
description: Načte slovník obsahující indexy a názvy všech grafů v určeném listu sešitu Excel.
type: docs
weight: 27
url: /cs/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metoda

Načte slovník, který obsahuje indexy a názvy všech grafů ve specifikovaném listu sešitu [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
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
* Třída [IExcelDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)