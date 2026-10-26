---
title: GetWorksheetNames()
second_title: Aspose.Slides C++ API 参考
description: 检索 Excel 工作簿中包含的所有工作表的名称。
type: docs
weight: 53
url: /zh/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() 方法

检索 [Excel](../../) 工作簿中包含的所有工作表的名称。

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### 返回值

工作表名称的列表
## 备注



示例： 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IList](../../../system.collections.generic/ilist/)
* 类 [String](../../../system/string/)
* 类 [ExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)