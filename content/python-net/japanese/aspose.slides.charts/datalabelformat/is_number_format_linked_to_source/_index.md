---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source プロパティ
読み書き **bool**.

### 備考
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            このプロパティは DataLabelCollection コレクション内の新しいデータラベルの IsNumberFormatLinkedToSource プロパティのデフォルト値を取得または設定します。
            Set this property with value also sets this value to the IsNumberFormatLinkedToSource property 
            このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも同じ値が設定されます
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 原因となり 
            すべての DataLabels[i].IsNumberFormatLinkedToSource は val に等しい).

### 定義:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)