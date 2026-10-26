---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
インデックスでノードまたはサブノードを削除します。


```python
def remove_node(self, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | ノードのゼロベースインデックス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | インデックスが 0 未満です。 または インデックスが兄弟の数以上です。 |


## remove_node(self, node_obj) {#ismartartnode}
ノードまたはサブノードを削除します。


```python
def remove_node(self, node_obj):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode) | 削除するノード。 |



### 参照
* クラス [`ISmartArtNode`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode)
* クラス [`ISmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartnodecollection)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)