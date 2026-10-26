---
title: get_Column()
second_title: Aspose.Slides for C++ API 参考
description: 获取单元格所在工作表中列的零基索引。只读 int32_t。
type: docs
weight: 40
url: /zh/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() 方法

获取单元格所在工作表中列的零基索引。只读 **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 参见

* 类 [ExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)