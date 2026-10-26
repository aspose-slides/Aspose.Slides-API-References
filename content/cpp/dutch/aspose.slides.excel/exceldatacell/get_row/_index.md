---
title: get_Row()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de nulgebaseerde index van de rij op in het werkblad waar de cel zich bevindt. Alleen-lezen int32_t.
type: docs
weight: 27
url: /nl/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() methode


Haalt de nulgebaseerde index van de rij op in het werkblad waar de cel zich bevindt. Alleen-lezen **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Zie ook

* Klasse [ExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)