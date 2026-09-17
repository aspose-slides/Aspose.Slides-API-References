---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/globallayoutslidecollection/add_clone/
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

異なるプレゼンテーション間でレイアウトをクローンする場合、レイアウトのマスターも
            ソースの書式設定を保持するためにクローンされる可能性があります。
            内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの
            複数のクローンの作成を防止します。
            マスター スライドの手動クローンは防止も登録もされません。

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
| dest_master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいレイアウトのマスター スライド。 |

### 備考

1) 新しいレイアウトは、対象プレゼンテーションで定義されたマスターにリンクされます。
            したがって、これは PowerPoint の「宛先のテーマを使用」オプションを使用したコピー/貼り付けの
            アナログです。
            2) このメソッドのアナログは、[`IMasterSlide.layout_slides`](/slides/python-net/ja/aspose.slides/imasterslide/layout_slides) プロパティでアクセスできる
            メソッド **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** です。

### 参照
* class [`GlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)