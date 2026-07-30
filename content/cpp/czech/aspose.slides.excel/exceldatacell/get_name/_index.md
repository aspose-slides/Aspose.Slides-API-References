---
title: get_Name()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Získá název buňky dat grafu.
type: docs
weight: 14
url: /cs/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metoda


Získá název buňky dat grafu.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Viz také

* Třída [String](../../../system/string/)
* Třída [ExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)