---
title: get_Value()
second_title: Aspose.Slides for C++ API 参考
description: "获取 Excel 单元格中包含的值。只读 System::Object."
type: docs
weight: 1
url: /zh/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() 方法

获取 [Excel](../../) 单元格中包含的值。只读 [System::Object](../../../system/object/)。

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [IExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)