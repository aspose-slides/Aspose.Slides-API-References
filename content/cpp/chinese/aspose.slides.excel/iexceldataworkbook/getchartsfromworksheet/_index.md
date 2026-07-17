---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API 参考
description: 检索一个字典，其中包含指定 Excel 工作簿的工作表中所有图表的索引和名称。
type: docs
weight: 27
url: /zh/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) 方法

检索一个字典，其中包含指定 [Excel](../../) 工作簿的工作表中所有图表的索引和名称。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 要搜索图表的工作表名称。 |

### 返回值

一个字典，其中键是图表索引，值是图表名称。

## 备注



示例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [IExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)