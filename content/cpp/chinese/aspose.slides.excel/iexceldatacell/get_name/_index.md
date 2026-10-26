---
title: get_Name()
second_title: Aspose.Slides C++ API 参考
description: "获取图表数据单元格的名称。只读 System::String."
type: docs
weight: 14
url: /zh/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() 方法


获取图表数据单元格的名称。只读 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## 备注


示例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## 另请参阅

* 类 [String](../../../system/string/)
* 类 [IExcelDataCell](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)