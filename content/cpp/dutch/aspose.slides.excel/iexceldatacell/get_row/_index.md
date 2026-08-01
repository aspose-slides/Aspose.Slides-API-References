---
title: get_Row()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de nul-gebaseerde index van de rij in het werkblad op waar de cel zich bevindt. Alleen-lezen int32_t.
type: docs
weight: 27
url: /nl/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() methode


Haalt de nul-gebaseerde index van de rij in het werkblad op waar de cel zich bevindt. Alleen-lezen **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Zie ook

* Klasse [IExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)