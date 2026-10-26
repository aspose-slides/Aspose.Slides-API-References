---
title: get_Column()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de nulgebaseerde index van de kolom in het werkblad op waar de cel zich bevindt. Alleen-lezen int32_t.
type: docs
weight: 40
url: /nl/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() methode


Krijgt de nulgebaseerde index van de kolom in het werkblad waar de cel zich bevindt. Alleen-lezen **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Zie ook

* Klasse [ExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)