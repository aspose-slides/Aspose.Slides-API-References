---
title: get_Name()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaadja a diagram adatcellájának a nevét.
type: docs
weight: 14
url: /hu/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() method


Visszaadja a diagram adatcellájának a nevét.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)