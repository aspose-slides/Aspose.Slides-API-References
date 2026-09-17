---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories プロパティ
[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが true の場合、二次カテゴリを取得します。
読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。

### 備考

[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが false の場合、この [`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティは None を返し、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは一次系列と二次系列の両方に使用されます。
[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが true の場合、この [`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティのデータは二次系列に使用され、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは一次系列に使用されます。

### 定義:
```python
@property
def secondary_categories(self):
    ...
```

### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* クラス [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)