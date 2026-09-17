---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name プロパティ
指定されたチャートのデータラベルのカテゴリ名表示動作を表します。  
True は、チャート上のデータラベルのカテゴリ名を表示します。False は、非表示にします。  
読み書き可能 **bool**。

### Remarks
この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowCategoryName プロパティのデフォルト値を取得または設定します。  
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowCategoryName プロパティにも同じ値が設定されます。  
（例: "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" は、すべての DataLabels[i].ShowCategoryName が val と等しくなる原因となります。）

### Definition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### See Also
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)