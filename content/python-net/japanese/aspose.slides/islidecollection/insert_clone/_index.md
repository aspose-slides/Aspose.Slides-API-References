---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
指定されたスライドのコピーをコレクションの指定位置に挿入します。

### 戻り値

挿入されたスライド。

```python
def insert_clone(self, index, source_slide):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローンするスライド。 |

### 備考

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。
内部レジストリは、自動的にクローンされたマスターを追跡し、同じマスタースライドの複数のクローン作成を防止するために使用されます。
マスタースライドの手動クローンは防止も登録もされません。
クローン処理をより細かく制御したい場合は、次を使用してください
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** または
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste**（スライドのクローン用）および
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide**（マスターのクローン用）。

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
指定されたスライドのコピーをコレクションの指定位置に挿入します。

### 戻り値

挿入されたスライド。

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローンするスライド。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。 |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
指定されたソーススライドのコピーをコレクションの指定位置に挿入します。
            適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）あるいは PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

### 戻り値

挿入されたスライド。

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| source_slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | クローンするスライド。 |
| dest_master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allow_clone_missing_layout | **bool** | 指定されたマスターに適切なレイアウトが存在しない場合、レイアウトはソーススライドの<br/><br/>            レイアウトがクローンされます（allowCloneMissingLayout が true の場合）または<br/><br/>            PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 指定されたマスターに適切なレイアウトが存在せず、allowCloneMissingLayout が false の場合にスローされます。 |

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)