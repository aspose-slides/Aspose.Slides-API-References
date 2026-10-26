---
title: GetWorksheetNames()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az Excel munkafüzetben található összes munkalap nevét.
type: docs
weight: 53
url: /hu/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metódus

A(z) [Excel](../../) munkafüzetben található összes munkalap nevét adja vissza.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### Visszatérési érték

A munkalap nevek listája
## Megjegyzések

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
* Osztály [ExcelDataWorkbook](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)