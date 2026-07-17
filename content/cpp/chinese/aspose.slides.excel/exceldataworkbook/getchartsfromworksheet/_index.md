---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API 参考
description: 检索一个字典，其中包含指定 Excel 工作簿中工作表的所有图表的索引和名称。
type: docs
weight: 40
url: /zh/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) 方法

检索一个字典，其中包含指定[Excel](../../)工作簿中工作表的所有图表的索引和名称。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 用于搜索图表的工作表的名称。 |

### 返回值

一个字典，其中键是图表索引，值是图表名称。

## 备注

示例：
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [ExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)