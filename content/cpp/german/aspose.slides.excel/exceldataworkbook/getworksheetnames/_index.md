---
title: GetWorksheetNames()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Namen aller Arbeitsblätter ab, die in der Excel-Arbeitsmappe enthalten sind.
type: docs
weight: 53
url: /de/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() Methode


Ruft die Namen aller Arbeitsblätter ab, die in der [Excel](../../) Arbeitsmappe enthalten sind.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Rückgabewert

Eine Liste von Arbeitsblattnamen
## Hinweise



Beispiel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelDataWorkbook](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)