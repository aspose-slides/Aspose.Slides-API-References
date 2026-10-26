---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de naam van de grafiekgegevenscel op. Alleen-lezen System::String."
type: docs
weight: 14
url: /nl/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() methode


Haalt de naam van de grafiekgegevenscel op. Alleen-lezen [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)