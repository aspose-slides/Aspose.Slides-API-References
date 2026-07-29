---
title: GetWorksheetNames()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar namnen på alla arbetsblad som finns i Excel-arbetsboken.
type: docs
weight: 40
url: /sv/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metod


Hämtar namnen på alla arbetsblad som finns i [Excel](../../) arbetsboken.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Returvärde

En lista med arbetsbladsnamn
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IList](../../../system.collections.generic/ilist/)
* Klass [String](../../../system/string/)
* Klass [IExcelDataWorkbook](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)