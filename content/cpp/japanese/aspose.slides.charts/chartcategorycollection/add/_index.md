---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションにカテゴリが存在する場合はそれを返します。存在しない場合は IChartDataCell から新しいチャートカテゴリを作成し、コレクションに追加します。
type: docs
weight: 92
url: /ja/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) メソッド


コレクションにカテゴリが存在する場合は、それを返します。存在しない場合は、[IChartDataCell](../../ichartdatacell/) から新しいチャートカテゴリを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) はチャートカテゴリの作成に使用されます。 |

### 戻り値

追加されたカテゴリ、または既存のカテゴリ。



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) メソッド


値から新しい[ChartCategory](../../chartcategory/) を作成し、コレクションに追加します。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | その値。 |

### 戻り値

追加された[IChartCategory](../../ichartcategory/)。
## 備考



このメソッドは、名前が AUTO_DATA のワークシートを追加し、すべての値をそのシートに追加します。[ChartDataWorkbook](../../chartdataworkbook/) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる最大の値の数は 16711680 を超えてはなりません。



## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)