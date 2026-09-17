---
title: data_source_type property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/stringordoublechartvalue/data_source_type/
weight: 80
---
## data_source_type プロパティ
Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble 
            property is actual in descendants. In other words it specifies the type 
            of value of the Data property.
            読み取り/書き込み [`DataSourceType`](/slides/python-net/ja/aspose.slides.charts/datasourcetype).

### 備考

For points in ChartDataPointCollection this property is read-only. 
            In this case for changing value of this property you can use one of the 
            ChartDataPointCollection.DataSourceTypeFor<...> properties.

### 定義:
```python
@property
def data_source_type(self):
    ...

@data_source_type.setter
def data_source_type(self, value):
    ...
```

### 参照
* 列挙体 [`DataSourceType`](/slides/python-net/ja/aspose.slides.charts/datasourcetype)
* クラス [`StringOrDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/stringordoublechartvalue)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)