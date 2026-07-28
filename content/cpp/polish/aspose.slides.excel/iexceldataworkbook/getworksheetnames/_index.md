---
title: GetWorksheetNames()
second_title: Aspose.Slides dla C++ – Referencja API
description: Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel.
type: docs
weight: 40
url: /pl/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metoda


Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Wartość zwracana

Lista nazw arkuszy
## Uwagi



Przykład: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IList](../../../system.collections.generic/ilist/)
* Klasa [String](../../../system/string/)
* Klasa [IExcelDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)