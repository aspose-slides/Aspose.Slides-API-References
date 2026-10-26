---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de naam van de grafiekgegevenscel op.
type: docs
weight: 14
url: /nl/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() methode

Haalt de naam van de grafiekgegevenscel op.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
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
* Klasse [ExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)