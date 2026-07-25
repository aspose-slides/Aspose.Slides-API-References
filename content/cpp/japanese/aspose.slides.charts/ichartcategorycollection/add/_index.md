---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションにカテゴリが存在する場合はそれを返します。存在しない場合は IChartDataCell から新しいチャートカテゴリを作成し、コレクションに追加します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) メソッド

コレクションにカテゴリが存在する場合はそれを返します。存在しない場合は [IChartDataCell](../../ichartdatacell/) から新しいチャートカテゴリを作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) を使用してチャートカテゴリを作成します。 |

### 戻り値

追加されたカテゴリ、または既存のカテゴリ。

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) メソッド

value から新しい [IChartCategory](../../ichartcategory/) を作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 値。 |

### 戻り値

追加された [IChartCategory](../../ichartcategory/)。

## 備考

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[IChartDataWorkbook](../../ichartdataworkbook/) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる最大の値の数は 16711680 を超えてはなりません。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCategory](../../ichartcategory/)
* クラス [IChartDataCell](../../ichartdatacell/)
* クラス [IChartCategoryCollection](../)
* クラス [Object](../../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)