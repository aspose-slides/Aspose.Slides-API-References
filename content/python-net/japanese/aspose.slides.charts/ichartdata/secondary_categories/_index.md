---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories プロパティ
二次カテゴリを取得します。[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合。
            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。


### Remarks

[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが false の場合、この [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) プロパティは None を返し、[`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータは一次および二次シリーズの両方に使用されます。
            [`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合、この [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) プロパティのデータは二次シリーズに使用され、[`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータは一次シリーズに使用されます。

### Definition:
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