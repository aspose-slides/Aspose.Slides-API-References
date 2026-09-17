---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
インデックスでノードまたはサブノードを削除します


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index が 0 未満です。 -or- index が兄弟ノード数以上です |


## remove_node(self, node) {#ismartartnode}
ノードまたはサブノードを削除します


```python
def remove_node(self, node):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode) | 削除するノード |



### 関連項目
* クラス [`ISmartArtNode`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode)
* クラス [`SmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/smartartnodecollection)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)