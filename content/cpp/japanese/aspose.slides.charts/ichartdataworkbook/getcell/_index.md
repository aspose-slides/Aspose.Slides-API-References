---
title: GetCell()
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの系列またはカテゴリに使用できるセルを取得します
type: docs
weight: 40
url: /ja/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) メソッド

チャートの系列またはカテゴリに使用できるセルを取得します

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ワークシートの名前。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 戻り値

[Cell](../../../aspose.slides/cell/) オブジェクト

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) メソッド

チャートの系列またはカテゴリに使用できるセルを取得します

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのインデックス。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 戻り値

[Cell](../../../aspose.slides/cell/) オブジェクト

## IChartDataWorkbook::GetCell(int32_t, System::String) メソッド

チャートの系列またはカテゴリに使用できるセルを取得します

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのインデックス。 |
| cellName | [System::String](../../../system/string/) | セルの名前。 |

### 戻り値

[Cell](../../../aspose.slides/cell/) オブジェクト

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) メソッド

チャートの系列またはカテゴリに使用できるセルを取得します

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのインデックス。 |
| cellName | [System::String](../../../system/string/) | セルの名前。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 値。 |

### 戻り値

[Cell](../../../aspose.slides/cell/) オブジェクト

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) メソッド

チャートの系列またはカテゴリに使用できるセルを取得します

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ワークシートのインデックス。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 値。 |

### 戻り値

[Cell](../../../aspose.slides/cell/) オブジェクト

## 参照

* タイプ定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [String](../../../system/string/)
* クラス [IChartDataWorkbook](../)
* クラス [Object](../../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)