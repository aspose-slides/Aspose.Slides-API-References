---
title: get_Name()
second_title: Aspose.Slides for C++ API 参考
description: 获取图表数据单元格的名称。
type: docs
weight: 14
url: /zh/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() 方法

获取图表数据单元格的名称。

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## 另见

* 类 [String](../../../system/string/)
* 类 [ExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)