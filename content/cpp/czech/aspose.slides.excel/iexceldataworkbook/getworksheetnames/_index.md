---
title: GetWorksheetNames()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Načte názvy všech listů obsažených v sešitu Excel.
type: docs
weight: 40
url: /cs/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metoda


Načte názvy všech listů obsažených v sešitu [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IList](../../../system.collections.generic/ilist/)
* Třída [String](../../../system/string/)
* Třída [IExcelDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)