---
title: get_Column()
second_title: Aspose.Slides pro C++ API Reference
description: Získá nulový index sloupce v listu, kde se buňka nachází. Pouze pro čtení int32_t.
type: docs
weight: 40
url: /cs/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metoda


Získá nulový index sloupce v listu, kde se buňka nachází. Pouze pro čtení **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Viz také

* Třída [ExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)