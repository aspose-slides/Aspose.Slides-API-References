---
title: GetWorksheetNames()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft die Namen aller Arbeitsblätter im Excel-Arbeitsbuch ab.
type: docs
weight: 40
url: /de/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() Methode

Ruft die Namen aller Arbeitsblätter im [Excel](../../) Arbeitsbuch ab.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```

### Rückgabewert

Eine Liste von Arbeitsblattnamen
## Bemerkungen

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
* Klasse [IExcelDataWorkbook](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)