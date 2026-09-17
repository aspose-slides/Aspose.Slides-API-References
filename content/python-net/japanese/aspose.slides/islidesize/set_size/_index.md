---
title: set_size method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
タイプでスライドサイズを設定し、既存のコンテンツをスケーリングします。

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ja/aspose.slides/slidesizetype) | 適用する事前定義済みのスライドサイズ。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype) | 使用するコンテンツのスケーリングモード。 |

### 備考
Assigning any value other than [`SlideSizeType.CUSTOM`](/slides/python-net/ja/aspose.slides/slidesizetype/CUSTOM) adjusts the [`ISlideSize.size`](/slides/python-net/ja/aspose.slides/islidesize/size)
            based on the selected type, while preserving [`ISlideSize.orientation`](/slides/python-net/ja/aspose.slides/islidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
スライドのサイズを明示的に設定し、既存のコンテンツをスケーリングします。

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | 新しいスライド幅（ポイント単位）。 |
| height | **float** | 新しいスライド高さ（ポイント単位）。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype) | 使用するコンテンツのスケーリングモード。 |

### 備考
This resets the [`ISlideSize.type`](/slides/python-net/ja/aspose.slides/islidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/ja/aspose.slides/slidesizetype/CUSTOM)
            and sets the [`ISlideSize.orientation`](/slides/python-net/ja/aspose.slides/islidesize/orientation).

### 参照
* クラス [`ISlideSize`](/slides/python-net/ja/aspose.slides/islidesize)
* 列挙型 [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype)
* 列挙型 [`SlideSizeType`](/slides/python-net/ja/aspose.slides/slidesizetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)