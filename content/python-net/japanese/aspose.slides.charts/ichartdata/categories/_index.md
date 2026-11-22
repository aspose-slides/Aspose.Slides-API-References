---
title: categories property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## カテゴリ プロパティ
プライマリ カテゴリを取得します（またはプライマリとセカンダリの両方のカテゴリ 
            if [`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが false の場合)。
            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。


### 備考

[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが false の場合は [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) 
            プロパティは None を返し、この [`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータはプライマリと 
            セカンダリシリーズの両方に使用されます。
            [`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合は [`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) 
            プロパティはセカンダリシリーズに使用され、この [`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータは 
            プライマリシリーズに使用されます。

### 定義:
```python
@property
def categories(self):
    ...
```


### 参照
* クラス [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)
* クラス [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)