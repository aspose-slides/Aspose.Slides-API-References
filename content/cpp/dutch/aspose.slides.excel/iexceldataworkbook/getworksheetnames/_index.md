---
title: GetWorksheetNames()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de namen op van alle werkbladen die zich in het Excel-werkboek bevinden.
type: docs
weight: 40
url: /nl/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method


Haalt de namen op van alle werkbladen die zich in het [Excel](../../) werkboek bevinden.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
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
* Klasse [IExcelDataWorkbook](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)