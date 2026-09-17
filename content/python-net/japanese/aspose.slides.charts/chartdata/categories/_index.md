---
title: categories property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories プロパティ
主カテゴリを取得します（[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが false の場合、主カテゴリと副カテゴリの両方を取得します）。 読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。

### 備考

[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが false の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティは None を返し、この [`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主系列と副系列の両方に使用されます。[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが true の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティのデータは副系列に使用され、 この [`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主系列に使用されます。

### 定義:
```python
@property
def categories(self):
    ...
```

### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* クラス [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)