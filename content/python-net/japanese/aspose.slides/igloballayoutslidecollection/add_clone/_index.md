---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

### 戻り値

追加されたスライド。

```python
def add_clone(self, source_layout):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローンするスライド。 |

### 備考

異なるプレゼンテーション間でレイアウトをクローンする場合、レイアウトのマスターもクローンされ、元の書式設定が保持されます。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスタースライドのクローンが複数作成されるのを防止します。マスタースライドの手動クローンは防止も登録もされません。

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

### 戻り値

追加されたスライド。

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローンするスライド。 |
| dest_master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいレイアウトのためのマスタースライド。 |

### 備考

新しいレイアウトは、宛先プレゼンテーションで定義されたマスターとリンクされます。したがって、PowerPoint の「宛先のテーマを使用」オプションを使用したコピー/貼り付けと同等です。

### 参照
* クラス [`IGlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/igloballayoutslidecollection)
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)