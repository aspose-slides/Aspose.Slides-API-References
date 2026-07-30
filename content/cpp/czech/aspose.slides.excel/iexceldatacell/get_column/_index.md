---
title: get_Column()
second_title: Aspose.Slides pro C++ referenci API
description: Získá index sloupce počínající od nuly v listu, kde se buňka nachází. Pouze pro čtení int32_t.
type: docs
weight: 40
url: /cs/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metoda

Získá index sloupce počínající od nuly v listu, kde se buňka nachází. Pouze pro čtení **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Poznámky

Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Viz také

* Třída [IExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)