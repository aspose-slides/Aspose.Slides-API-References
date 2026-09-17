---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source プロパティ
Read/write **bool**.

### 備考

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            プロパティは新しいデータラベルに対する IsNumberFormatLinkedToSource プロパティのデフォルト値を取得または設定します
            DataLabelCollection コレクション内のラベルに対して。
            Set this property with value also sets this value to the IsNumberFormatLinkedToSource property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to 
            all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

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
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)