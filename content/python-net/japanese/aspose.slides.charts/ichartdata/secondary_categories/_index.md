---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## secondary_categories プロパティ
[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合、二次カテゴリを取得します。
            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。

### 備考
[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが false の場合、この [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) 
            プロパティは None を返し、[`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータは一次 
            および二次シリーズに使用されます。
[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合、データは 
            この [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) プロパティは二次シリーズに使用され、データ 
            [`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティは一次シリーズに使用されます。

### 定義:
```python
@property
def secondary_categories(self):
    ...
```

### 参照
* クラス [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)
* クラス [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)