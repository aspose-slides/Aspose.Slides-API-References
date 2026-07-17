---
title: GetCell()
second_title: Aspose.Slides for C++ API 参考
description: 检索指定工作表中的单元格，使用其索引和单元格坐标。
type: docs
weight: 27
url: /zh/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法

检索指定工作表中的单元格，使用其索引和单元格坐标。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### 返回值

指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法

检索指定工作表中的单元格，使用其名称和单元格坐标。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### 返回值

指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) 方法

检索指定工作表中的单元格，使用其索引和 Excel 样式的单元格名称（例如 "B2"）。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### 返回值

指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) 方法

检索指定工作表中的单元格，使用 Excel 样式的单元格名称（例如 "B2"）。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### 返回值

指定位置的单元格。

## 备注

示例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IExcelDataCell](../../iexceldatacell/)
* 类 [ExcelDataWorkbook](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)