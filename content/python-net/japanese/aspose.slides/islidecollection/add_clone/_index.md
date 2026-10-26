---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
指定されたスライドのコピーをコレクションの末尾に追加します。

### Returns
新しいスライド。

```python
def add_clone(self, source_slide):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |

### Remarks
異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。  
            内部レジストリは、自動的にクローンされたマスターを追跡し、  
            同じマスター スライドの複数のクローンが作成されるのを防止します。  
            マスター スライドの手動クローンは、阻止も登録もされません。  
            クローン処理をより詳細に制御したい場合は、以下を使用してください  
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** または  
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** を使用してスライドをクローンし、  
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** または  
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** を使用してレイアウトをクローンし、  
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** を使用してマスターをクローンします。

## add_clone(self, source_slide, section) {#islide-isection}
指定されたスライドのコピーを指定セクションの末尾に追加します。

### Returns
新しいスライド。

```python
def add_clone(self, source_slide, section):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | 新しいスライドのセクション。 |

### Exceptions
| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) |  |

## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
指定されたスライドのコピーをコレクションの末尾に追加します。

### Returns
新しいスライド。

```python
def add_clone(self, source_slide, dest_layout):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | 新しいスライドのレイアウト スライド。 |

## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
指定されたソース スライドのコピーをコレクションの末尾に追加します。  
適切なレイアウトが自動的に指定されたマスターから選択されます（適切なレイアウトは、ソース スライドの Type または Name と同じレイアウト）。適切なレイアウトが存在しない場合、ソース スライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

### Returns
新しいスライド。

```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| dest_master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいスライドのマスター スライド。 |
| allow_clone_missing_layout | **bool** | 指定されたマスターに適切なレイアウトがない場合、ソース スライドのレイアウトがクローンされます（allowCloneMissingLayout が true のとき）または PptxEditException がスローされます（allowCloneMissingLayout が false のとき）。 |

### Exceptions
| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 指定されたマスターに適切なレイアウトがなく、allowCloneMissingLayout が false の場合にスローされます。 |

### See Also
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)