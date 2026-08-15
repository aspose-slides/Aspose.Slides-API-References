---
title: GetCell()
second_title: Aspose.Slides for C++ API 參考
description: 使用索引和儲存格座標從指定的工作表檢索儲存格。
type: docs
weight: 27
url: /zh-hant/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法

使用索引和儲存格座標從指定的工作表檢索儲存格。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| row | **int32_t** | 儲存格的零基列索引。 |
| column | **int32_t** | 儲存格的零基欄索引。 |

### 回傳值

指定位置的儲存格。

## 備註

範例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法

使用名稱和儲存格座標從指定的工作表檢索儲存格。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| row | **int32_t** | 儲存格的零基列索引。 |
| column | **int32_t** | 儲存格的零基欄索引。 |

### 回傳值

指定位置的儲存格。

## 備註

範例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) 方法

使用索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表檢索儲存格。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| cellName | [System::String](../../../system/string/) | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

### 回傳值

指定位置的儲存格。

## 備註

範例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) 方法

使用 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表檢索儲存格。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| cellName | [System::String](../../../system/string/) | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

### 回傳值

指定位置的儲存格。

## 備註

範例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IExcelDataCell](../../iexceldatacell/)
* 類別 [ExcelDataWorkbook](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)