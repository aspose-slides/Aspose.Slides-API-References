---
title: GetWorksheetNames()
second_title: Odwołanie API Aspose.Slides dla C++
description: Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel.
type: docs
weight: 53
url: /pl/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metoda


Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
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
* Klasa [ExcelDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)