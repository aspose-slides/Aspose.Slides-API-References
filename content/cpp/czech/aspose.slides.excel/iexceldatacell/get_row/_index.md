---
title: get_Row()
second_title: Aspose.Slides pro C++ API Reference
description: Získá nulový index řádku v listu, kde se buňka nachází. Pouze pro čtení int32_t.
type: docs
weight: 27
url: /cs/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() metoda


Získá nulový index řádku v listu, kde se buňka nachází. Pouze pro čtení **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Viz také

* Třída [IExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)