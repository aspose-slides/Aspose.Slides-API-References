---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
スライド上のすべてのシェイプの配置を変更します。シェイプをスライドの余白または端に合わせるか、相互に相対的に配置します。


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ja/aspose.slides/shapesalignmenttype) | 適用される配置のタイプを決定します。 |
| align_to_slide | **bool** | true の場合、シェイプはスライドの端に対して配置されます。 |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 親スライド。 |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
グループシェイプ内のすべてのシェイプの配置を変更します。シェイプをスライドの余白または端に合わせるか、相互に相対的に配置します。


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ja/aspose.slides/shapesalignmenttype) | 適用される配置のタイプを決定します。 |
| align_to_slide | **bool** | true の場合、シェイプはスライドの端に対して配置されます。 |
| group_shape | [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape) | 親グループシェイプ。 |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
スライド上の選択されたシェイプの配置を変更します。シェイプをスライドの余白または端に合わせるか、相互に相対的に配置します。


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ja/aspose.slides/shapesalignmenttype) | 適用される配置のタイプを決定します。 |
| align_to_slide | **bool** | true の場合、シェイプはスライドの端に対して配置されます。 |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 親スライド。 |
| shape_indexes | **List[int]** | 配置対象となるシェイプのインデックス。 |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
グループシェイプ内の選択されたシェイプの配置を変更します。シェイプをスライドの余白または端に合わせるか、相互に相対的に配置します。


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ja/aspose.slides/shapesalignmenttype) | 適用される配置のタイプを決定します。 |
| align_to_slide | **bool** | true の場合、シェイプはスライドの端に対して配置されます。 |
| group_shape | [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape) | 親グループシェイプ。 |
| shape_indexes | **List[int]** | 配置対象となるシェイプのインデックス。 |



### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)
* 列挙体 [`ShapesAlignmentType`](/slides/python-net/ja/aspose.slides/shapesalignmenttype)
* クラス [`SlideUtil`](/slides/python-net/ja/aspose.slides.util/slideutil)
* モジュール [`aspose.slides.util`](/slides/python-net/ja/aspose.slides.util)
* ライブラリ [`Aspose.Slides`](/slides/python-net)