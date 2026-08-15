---
title: GetCell()
second_title: Aspose.Slides for C++ API 參考
description: 使用索引與儲存格座標從指定的工作表取得儲存格。
type: docs
weight: 14
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法


取得指定工作表中，依索引與儲存格座標的儲存格。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| row | **int32_t** | 儲存格的零基列索引。 |
| column | **int32_t** | 儲存格的零基欄索引。 |

### 傳回值

指定位置的儲存格。

## 备注



範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法


取得指定工作表中，依名稱與儲存格座標的儲存格。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| row | **int32_t** | 儲存格的零基列索引。 |
| column | **int32_t** | 儲存格的零基欄索引。 |

### 傳回值

指定位置的儲存格。

## 备注



範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) 方法


取得指定工作表中，依索引與 Excel 風格儲存格名稱（例如 "B2"）的儲存格。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的零基索引。 |
| cellName | [System::String](../../../system/string/) | Excel 風格的儲存格參照（例如 "A1"，"C5"）。 |

### 傳回值

指定位置的儲存格。

## 备注



範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) 方法


取得指定工作表中，依 Excel 風格儲存格名稱（例如 "B2"）的儲存格。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| cellName | [System::String](../../../system/string/) | Excel 風格的儲存格參照（例如 "A1"，"C5"）。 |

### 傳回值

指定位置的儲存格。

## 备注



範例：
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IExcelDataCell](../../iexceldatacell/)
* 類別 [IExcelDataWorkbook](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Excel](../../)
* 函式庫 [Aspose.Slides](../../../)