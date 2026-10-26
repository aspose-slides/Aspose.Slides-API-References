---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            コレクションがインデックス `index`==N のデータポイントを含んでいない場合
            (このコレクションのデータポイント数が N 以下の場合)
            不足しているデータポイントを追加し、最後のデータポイント（要求されたインデックスを持つもの）を返します。
            例として、コレクションのインデックスは {0, 1, 2} で、要求されたインデックスは 5 です。
            このとき、メソッドは不足しているデータポイントを追加します: {0, 1, 2, 3, 4, 5}。そしてインデックス 5 のデータポイントを返します。

### 戻り値

要求されたインデックスのデータポイントを返します。



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | インデックス。 |



### 参照
* クラス [`ChartDataPointCollection`](/slides/python-net/ja/aspose.slides.charts/chartdatapointcollection)
* クラス [`IChartDataPoint`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)