---
title: get_Row()
second_title: Aspose.Slides C++ API Referenciája
description: Visszaadja a cellát tartalmazó munkalapon a sor nullaalapú indexét. Csak olvasható int32_t.
type: docs
weight: 27
url: /hu/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metódus


Visszaadja a cellát tartalmazó munkalapon a sor nullaalapú indexét. Csak olvasható **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Lásd még

* Osztály [ExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)