---
title: GetWorksheetNames()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de namen op van alle werkbladen die in de Excel-werkmap zitten.
type: docs
weight: 53
url: /nl/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() methode


Haal de namen op van alle werkbladen die zich in de [Excel](../../) werkmap bevinden.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Retourwaarde

Een lijst met werkbladnamen
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelDataWorkbook](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)