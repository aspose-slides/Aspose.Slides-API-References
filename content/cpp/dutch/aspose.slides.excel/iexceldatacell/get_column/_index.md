---
title: get_Column()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de nulgebaseerde index van de kolom in het werkblad op waar de cel zich bevindt. Alleen-lezen int32_t.
type: docs
weight: 40
url: /nl/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() methode


Haalt de nulgebaseerde index van de kolom in het werkblad op waar de cel zich bevindt. Alleen-lezen **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Zie ook

* Klasse [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)