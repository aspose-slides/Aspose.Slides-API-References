---
title: GetCells()
second_title: Aspose.Slides for C++ API 参考
description: 检索工作簿中与指定公式匹配的单元格集合。
type: docs
weight: 14
url: /zh/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) 方法

检索工作簿中与指定公式匹配的单元格集合。

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 用于标识目标单元格的公式或范围表达式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | **bool** | 如果为 **true**，隐藏的单元格（例如隐藏的行或列中的单元格）将从结果中排除。 |

### 返回值

只读的单元格列表，其中的单元格匹配指定的公式。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* 类 [IExcelDataCell](../../iexceldatacell/)
* 类 [String](../../../system/string/)
* 类 [ExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)