---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: コレクションに新しいセルを追加します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) メソッド

コレクションに新しいセルを追加します。

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 追加する新しいセル。 |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) メソッド

指定された値から [ChartDataCell](../../chartdatacell/) を作成し、コレクションに追加します。

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 値。 |

## 備考

このメソッドは名前が AUTO_DATA のワークシートを追加し、そこにすべての値を追加します。[ChartDataWorkbook](../../chartdataworkbook/) を使用して [Cell](../../../aspose.slides/cell/) の値を追加または編集する場合は、このワークシートを使用しないでください。このメソッドで追加できる値の最大数は 16711680 を超えてはなりません。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [ChartCellCollection](../)
* クラス [Object](../../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)