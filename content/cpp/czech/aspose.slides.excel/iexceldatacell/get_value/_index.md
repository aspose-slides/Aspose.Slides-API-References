---
title: get_Value()
second_title: Aspose.Slides pro C++ – reference API
description: "Získá hodnotu obsaženou v buňce Excel. Pouze pro čtení System::Object."
type: docs
weight: 1
url: /cs/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() metoda


Získá hodnotu obsaženou v buňce [Excel](../../). Pouze pro čtení [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [IExcelDataCell](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)