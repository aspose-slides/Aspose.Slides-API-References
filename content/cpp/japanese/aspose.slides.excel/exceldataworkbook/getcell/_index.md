---
title: GetCell()
second_title: Aspose.Slides for C++ API リファレンス
description: インデックスとセル座標を使用して、指定されたワークシートからセルを取得します。
type: docs
weight: 27
url: /ja/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) メソッド


指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのゼロベースインデックス。 |
| row | **int32_t** | セルの行のゼロベースインデックス。 |
| column | **int32_t** | セルの列のゼロベースインデックス。 |

### 戻り値

指定された場所のセル。

## 備考



例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) メソッド


指定されたワークシートから、名前とセル座標を使用してセルを取得します。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ワークシートの名前。 |
| row | **int32_t** | セルの行のゼロベースインデックス。 |
| column | **int32_t** | セルの列のゼロベースインデックス。 |

### 戻り値

指定された場所のセル。

## 備考



例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) メソッド


指定されたワークシートから、インデックスと Excel スタイルのセル名（例: "B2"）を使用してセルを取得します。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのゼロベースインデックス。 |
| cellName | [System::String](../../../system/string/) | Excel スタイルのセル参照（例: "A1", "C5"）。 |

### 戻り値

指定された場所のセル。

## 備考



例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) メソッド


指定されたワークシートから、Excel スタイルのセル名（例: "B2"）を使用してセルを取得します。

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ワークシートの名前。 |
| cellName | [System::String](../../../system/string/) | Excel スタイルのセル参照（例: "A1", "C5"）。 |

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
* クラス [ExcelDataWorkbook](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)