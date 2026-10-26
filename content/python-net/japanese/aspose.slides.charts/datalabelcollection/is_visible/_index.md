---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible プロパティ
False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) は false になります)。 読み取り専用 **bool**。


### 備考

データ ラベルがデフォルトで表示されている場合は、Hide() メソッドでデフォルトで非表示にできます。 ただし、データ ラベルがデフォルトで表示されていない場合 (IsVisible は false) は、DefaultDataLabelFormat プロパティの Show*-flags (ShowValue, ...) を true に設定することで、データ ラベルを「デフォルトで表示」できるようになります。

### 定義:
```python
@property
def is_visible(self):
    ...
```


### 関連項目
* クラス [`DataLabelCollection`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)