---
title: GetCell()
second_title: Aspose.Slides for C++ API 参考
description: 使用工作表的索引和单元格坐标检索指定工作表中的单元格。
type: docs
weight: 14
url: /zh/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法

检索指定工作表中的单元格，使用其索引和单元格坐标。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| row | **int32_t** | 单元格的零基行索引。 |
| column | **int32_t** | 单元格的零基列索引。 |

### 返回值

位于指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法

检索指定工作表中的单元格，使用其名称和单元格坐标。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名称。 |
| row | **int32_t** | 单元格的零基行索引。 |
| column | **int32_t** | 单元格的零基列索引。 |

### 返回值

位于指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) 方法

检索指定工作表中的单元格，使用其索引和 Excel 样式的单元格名称（例如 "B2"）。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| cellName | [System::String](../../../system/string/) | Excel 样式的单元格引用（例如 "A1", "C5"）。 |

### 返回值

位于指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) 方法

检索指定工作表中的单元格，使用 Excel 样式的单元格名称（例如 "B2"）。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名称。 |
| cellName | [System::String](../../../system/string/) | Excel 样式的单元格引用（例如 "A1", "C5"）。 |

### 返回值

位于指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IExcelDataCell](../../iexceldatacell/)
* 类 [IExcelDataWorkbook](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Excel](../../)
* 库 [Aspose.Slides](../../../)