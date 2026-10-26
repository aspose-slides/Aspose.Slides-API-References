---
title: get_Name()
second_title: Aspose.Slides for C++ API referencia
description: "Visszaadja a diagram adatcellájának nevét. Csak olvasható System::String."
type: docs
weight: 14
url: /hu/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metódus


Visszaadja a diagram adatcellájának nevét. Csak olvasható [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Osztály [IExcelDataCell](../)
* Névterület [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)