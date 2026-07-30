---
title: get_Row()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací nulový index řádku v listu, kde se buňka nachází. Pouze ke čtení int32_t.
type: docs
weight: 27
url: /cs/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metoda

Získá nulový index řádku v listu, kde se buňka nachází. Pouze ke čtení **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Poznámky

Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Viz také

* Třída [ExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)