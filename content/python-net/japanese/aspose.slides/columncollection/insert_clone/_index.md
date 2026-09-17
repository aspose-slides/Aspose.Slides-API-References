---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/columncollection/insert_clone/
weight: 20
---
## insert_clone(self, index, templ, with_attached_columns) {#int-icolumn-bool}
指定されたテンプレート列のコピーを作成し、テーブル内の指定位置に挿入します。

### 戻り値

挿入された列。

```python
def insert_clone(self, index, templ, with_attached_columns):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しい列のインデックス。 |
| templ | [`IColumn`](/slides/python-net/ja/aspose.slides/icolumn) | テンプレートとして使用される列。 |
| with_attached_columns | **bool** | True to copy also all columns attached to the template column. |

### 参照
* class [`ColumnCollection`](/slides/python-net/ja/aspose.slides/columncollection)
* class [`IColumn`](/slides/python-net/ja/aspose.slides/icolumn)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)