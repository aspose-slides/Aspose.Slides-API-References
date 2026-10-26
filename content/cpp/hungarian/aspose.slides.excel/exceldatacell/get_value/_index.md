---
title: get_Value()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri az Excel cellában tárolt értéket.
type: docs
weight: 1
url: /hu/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() metódus


Lekéri a(z) [Excel](../../) cellában tárolt értéket.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [ExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)