---
title: get_Value()
second_title: Aspose.Slides for C++ API Reference
description: Gets the value contained in the Excel cell.
type: docs
weight: 1
url: /aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() method


Gets the value contained in the [Excel](../../) cell.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)