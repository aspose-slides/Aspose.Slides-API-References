---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu kalkulacyjnym skoroszytu Excel.
type: docs
weight: 27
url: /pl/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metoda

Zwraca słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu kalkulacyjnym [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, w którym należy wyszukać wykresy. |

### Wartość zwracana

Słownik, w którym kluczem jest indeks wykresu, a wartością – nazwa wykresu.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IDictionary](../../../system.collections.generic/idictionary/)
* Klasa [String](../../../system/string/)
* Klasa [IExcelDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)