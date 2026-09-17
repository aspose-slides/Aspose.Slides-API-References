---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name プロパティ
指定されたチャートのデータ ラベルのカテゴリ名の表示動作を表します。
True は、チャート上のデータ ラベルのカテゴリ名を表示します。False は、非表示にします。
読み取り/書き込み **bool**。

### 備考
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            このプロパティは、新しいデータ 
            ラベルの ShowCategoryName プロパティのデフォルト値を取得または設定します。
            このプロパティに値を設定すると、 
            DataLabelCollection コレクション内のすべてのデータ ラベルの ShowCategoryName プロパティにも同じ値が設定されます
            (例: "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" は、 
            すべての DataLabels[i].ShowCategoryName が val に等しくなることを意味します)。

### 定義:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)