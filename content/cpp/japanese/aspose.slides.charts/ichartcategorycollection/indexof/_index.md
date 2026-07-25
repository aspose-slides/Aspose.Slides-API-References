---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された IChartCategory を検索し、Collection 全体で最初に出現した位置の0ベースインデックスを返します
type: docs
weight: 66
url: /ja/aspose.slides.charts/ichartcategorycollection/indexof/
---
## IChartCategoryCollection::IndexOf(System::SharedPtr\<IChartCategory\>) メソッド

指定された[IChartCategory](../../ichartcategory/)を検索し、Collection全体内で最初に出現した位置の0から始まるインデックスを返します。

```cpp
virtual int32_t Aspose::Slides::Charts::IChartCategoryCollection::IndexOf(System::SharedPtr<IChartCategory> value)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCategory](../../ichartcategory/)\> | [Chart](../../chart/) カテゴリ。 |

## 戻り値

CollectionBase全体内で value が最初に出現した位置の0から始まるインデックス（見つかった場合）。見つからない場合は -1 を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCategory](../../ichartcategory/)
* クラス [IChartCategoryCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)