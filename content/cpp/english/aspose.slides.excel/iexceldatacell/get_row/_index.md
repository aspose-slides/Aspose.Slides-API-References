---
title: get_Row()
second_title: Aspose.Slides for C++ API Reference
description: Gets the zero-based index of the row in the worksheet where the cell is located. Read-only int32_t.
type: docs
weight: 27
url: /aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() method


Gets the zero-based index of the row in the worksheet where the cell is located. Read-only **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## See Also

* Class [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)