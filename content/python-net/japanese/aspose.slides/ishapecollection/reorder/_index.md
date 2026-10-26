---
title: reorder method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。


```python
def reorder(self, index, shape):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | シェイプが配置される、ゼロベースの対象インデックス。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | コレクション内で移動する [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |


## reorder(self, index, shapes) {#int-listishape}
指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから配置します。


```python
def reorder(self, index, shapes):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 最初に指定されたシェイプが配置される、ゼロベースの対象インデックス；<br/><br/>            その後のシェイプは指定された順序で続きます。 |
| shapes | **List[IShape]** | コレクション内で移動する、1つ以上の [`IShape`](/slides/python-net/ja/aspose.slides/ishape) インスタンス。 |



### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)