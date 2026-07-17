---
title: get_Row()
second_title: Aspose.Slides C++ API 参考
description: 获取单元格所在工作表中行的零基索引。只读 int32_t。
type: docs
weight: 27
url: /zh/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() 方法

获取单元格所在工作表中行的零基索引。只读 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## 备注

示例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## 参见

* 类 [IExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)