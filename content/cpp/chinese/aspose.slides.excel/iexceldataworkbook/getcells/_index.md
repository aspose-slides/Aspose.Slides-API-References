---
title: GetCells()
second_title: Aspose.Slides for C++ API 参考
description: 检索工作簿中与指定公式匹配的单元格集合。
type: docs
weight: 1
url: /zh/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) 方法

检索工作簿中与指定公式匹配的单元格集合。

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 用于标识目标单元格的公式或范围表达式（例如 “Sheet1!A1:B3”）。 |
| skipHiddenCells | **bool** | 如果 **true**，隐藏的单元格（例如隐藏的行或列中的单元格）将从结果中排除。 |

### 返回值

只读列表，包含与指定公式匹配的单元格。

## 备注



示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* 类 [IExcelDataCell](../../iexceldatacell/)
* 类 [String](../../../system/string/)
* 类 [IExcelDataWorkbook](../)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)