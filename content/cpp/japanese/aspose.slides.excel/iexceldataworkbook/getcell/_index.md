---
title: GetCell()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。
type: docs
weight: 14
url: /ja/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) メソッド

指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのゼロベースインデックス。 |
| row | **int32_t** | セルのゼロベース行インデックス。 |
| column | **int32_t** | セルのゼロベース列インデックス。 |

### 戻り値

指定された場所のセル。

## 備考

例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) メソッド

指定されたワークシートから、名前とセル座標を使用してセルを取得します。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ワークシートの名前。 |
| row | **int32_t** | セルのゼロベース行インデックス。 |
| column | **int32_t** | セルのゼロベース列インデックス。 |

### 戻り値

指定された場所のセル。

## 備考

例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) メソッド

インデックスと Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのゼロベースインデックス。 |
| cellName | [System::String](../../../system/string/) | Excel 形式のセル参照（例: "A1", "C5"）。 |

### 戻り値

指定された場所のセル。

## 備考

例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) メソッド

Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ワークシートの名前。 |
| cellName | [System::String](../../../system/string/) | Excel 形式のセル参照（例: "A1", "C5"）。 |

### 戻り値

指定された場所のセル。

## 備考

例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IExcelDataCell](../../iexceldatacell/)
* クラス [IExcelDataWorkbook](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)