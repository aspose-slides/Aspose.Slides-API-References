---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
指定されたスライドのコピーをコレクションの末尾に追加します。

### 戻り値

新しいスライド。



```python
def add_clone(self, source_slide):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |

### 備考

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスタースライドの複数のクローンの作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は、以下を使用してください
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** または
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** をスライドのクローンに、
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** または
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** をレイアウトのクローンに、
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** をマスターのクローンに使用します。


## add_clone(self, source_slide, section) {#islide-isection}
指定されたスライドのコピーを指定されたセクションの末尾に追加します。

### 戻り値

新しいスライド。



```python
def add_clone(self, source_slide, section):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| section | [`ISection`](/slides/python-net/ja/aspose.slides/isection) | 新しいスライドのセクション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
指定されたスライドのコピーをコレクションの末尾に追加します。

### 戻り値

新しいスライド。



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。 |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じタイプまたは名前を持つレイアウトです）。適切なレイアウトが存在しない場合、レイアウトは <br/><br/> ソーススライドのものがクローンされます（allowCloneMissingLayout が true の場合）または <br/><br/> PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

### 戻り値

新しいスライド。



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローン対象のスライド。 |
| dest_master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allow_clone_missing_layout | **bool** | 指定されたマスターに適切なレイアウトがない場合、レイアウトは <br/><br/> ソーススライドのものがクローンされます（allowCloneMissingLayout が true の場合）または <br/><br/> PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 指定されたマスターに適切なレイアウトがなく、allowCloneMissingLayout が false の場合にスローされます。 |



### 関連項目
* class [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* class [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* class [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* class [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* class [`SlideCollection`](/slides/python-net/ja/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)