---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションに新しいセルを追加します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) メソッド


コレクションに新しいセルを追加します。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 追加する新しいセル。 |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) メソッド


指定された値から[IChartDataCell](../../ichartdatacell/)を作成し、コレクションに追加します。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 値。 |

## 備考



このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[IChartDataWorkbook](../../ichartdataworkbook/) を使用して [Cell](../../../aspose.slides/cell/) の値を追加または編集する場合は、このワークシートを使用しないでください。このメソッドで追加できる値の最大数は 16711680 を超えてはなりません。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartCellCollection](../)
* クラス [Object](../../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)