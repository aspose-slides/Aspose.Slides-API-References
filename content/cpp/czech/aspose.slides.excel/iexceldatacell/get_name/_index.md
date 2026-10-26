---
title: get_Name()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá název buňky dat grafu. Pouze pro čtení System::String."
type: docs
weight: 14
url: /cs/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metoda


Získá název buňky dat grafu. Pouze pro čtení [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Třída [IExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)