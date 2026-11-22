---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 130
---
## is_visible プロパティ
False は、データ ラベルがデフォルトで表示されないことを意味します（したがって DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) が false になります）。
読み取り専用 **bool**。

### 備考
データ ラベルがデフォルトで表示されている場合は、Hide() メソッドでデフォルトで非表示にすることができます。
ただし、データ ラベルがデフォルトで表示されていない場合（IsVisible が false）には、DefaultDataLabelFormat プロパティの Show*-flags (ShowValue, ...) を true に設定することで、データ ラベルを「デフォルトで表示」させることができます。

### 定義:
```python
@property
def is_visible(self):
    ...
```

### 参照
* クラス [`IDataLabelCollection`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)