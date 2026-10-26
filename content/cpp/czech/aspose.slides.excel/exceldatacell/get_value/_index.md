---
title: get_Value()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Získá hodnotu obsaženou v buňce Excel.
type: docs
weight: 1
url: /cs/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() metoda

Získá hodnotu obsaženou v buňce [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```


## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [ExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)