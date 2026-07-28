---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel.
type: docs
weight: 40
url: /pl/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metoda

Zwraca słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, w którym wyszukiwane są wykresy. |

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDictionary](../../../system.collections.generic/idictionary/)
* Klasa [String](../../../system/string/)
* Klasa [ExcelDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)