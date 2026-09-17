---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
指定されたレイアウト スライドのコピーをコレクションの指定位置に挿入します。

### 戻り値

挿入されたスライド。

```python
def insert_clone(self, index, source_layout):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローンするスライド。 |

### 備考

このレイアウト スライドのコレクションでは、新しいレイアウトは親マスタースライドにリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けと同等です。

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)