---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de waarde op die zich in de Excel-cel bevindt.
type: docs
weight: 1
url: /nl/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() methode


Haalt de waarde op die zich in de [Excel](../../) cel bevindt.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)