---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API 参考
description: 检索 Excel 工作簿中包含的所有工作表的名称。
type: docs
weight: 40
url: /zh/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() 方法


检索 [Excel](../../) 工作簿中所有工作表的名称。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### 返回值

工作表名称的列表
## 备注



示例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IList](../../../system.collections.generic/ilist/)
* 类 [String](../../../system/string/)
* 类 [IExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)