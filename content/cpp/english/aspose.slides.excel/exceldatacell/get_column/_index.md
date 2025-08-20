---
title: get_Column()
second_title: Aspose.Slides for C++ API Reference
description: Gets the zero-based index of the column in the worksheet where the cell is located. Read-only int32_t.
type: docs
weight: 40
url: /aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() method


Gets the zero-based index of the column in the worksheet where the cell is located. Read-only **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## See Also

* Class [ExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)