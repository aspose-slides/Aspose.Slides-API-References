---
title: GetWorksheetNames()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar namnen på alla kalkylblad som finns i Excel-arbetsboken.
type: docs
weight: 53
url: /sv/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metod


Hämtar namnen på alla kalkylblad som finns i arbetsboken [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Returvärde

En lista med namn på kalkylblad
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
* Klass [ExcelDataWorkbook](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)