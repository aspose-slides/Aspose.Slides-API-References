---
title: GetWorksheetNames()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Načte názvy všech listů obsažených v sešitu Excel.
type: docs
weight: 53
url: /cs/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metoda


Načte názvy všech listů obsažených v sešitu [Excel](../../) workbooku.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Návratová hodnota

Seznam názvů listů
## Poznámky



Příklad: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IList](../../../system.collections.generic/ilist/)
* Třída [String](../../../system/string/)
* Třída [ExcelDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)