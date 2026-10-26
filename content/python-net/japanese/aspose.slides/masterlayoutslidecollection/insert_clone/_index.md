---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。

### 戻り値

挿入されたスライド。

```python
def insert_clone(self, index, source_layout):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローンするスライド。 |

### 備考

新しいレイアウトは、このレイアウトスライドコレクションの親マスタースライドにリンクされます。  
したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けと同等です。

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)