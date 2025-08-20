---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: Gets the name of the chart data cell.
type: docs
weight: 14
url: /aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() method


Gets the name of the chart data cell.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## See Also

* Class [String](../../../system/string/)
* Class [ExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)