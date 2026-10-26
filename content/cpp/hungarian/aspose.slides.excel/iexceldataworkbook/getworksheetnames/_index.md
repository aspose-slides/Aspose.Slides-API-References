---
title: GetWorksheetNames()
second_title: Aspose.Slides C++ API referencia
description: Lekéri az Excel munkafüzetben található összes munkalap nevét.
type: docs
weight: 40
url: /hu/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metódus


A lekéri az összes munkalap nevét, amely a [Excel](../../) munkafüzetben található.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Visszatérési érték

A munkalapnevek listája
## Megjegyzés



Példa: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IList](../../../system.collections.generic/ilist/)
* Osztály [String](../../../system/string/)
* Osztály [IExcelDataWorkbook](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)