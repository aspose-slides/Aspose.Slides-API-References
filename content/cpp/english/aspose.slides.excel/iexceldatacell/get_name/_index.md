---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the name of the chart data cell. Read-only System::String."
type: docs
weight: 14
url: /aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() method


Gets the name of the chart data cell. Read-only [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Class [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)