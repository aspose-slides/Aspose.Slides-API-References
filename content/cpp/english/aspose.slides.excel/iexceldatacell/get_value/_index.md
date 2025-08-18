---
title: get_Value()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the value contained in the Excel cell. Read-only System::Object."
type: docs
weight: 1
url: /aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() method


Gets the value contained in the [Excel](../../) cell. Read-only [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
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
* Class [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)