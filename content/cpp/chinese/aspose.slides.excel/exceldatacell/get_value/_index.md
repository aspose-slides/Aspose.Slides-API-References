---
title: get_Value()
second_title: Aspose.Slides for C++ API 参考
description: 获取 Excel 单元格中包含的值。
type: docs
weight: 1
url: /zh/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() 方法

获取 [Excel](../../) 单元格中包含的值。

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## 备注


示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [ExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)