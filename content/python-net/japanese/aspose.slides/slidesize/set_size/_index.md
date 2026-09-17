---
title: set_size method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
type によってスライドのサイズを設定し、既存のコンテンツをスケーリングします。


```python
def set_size(self, type, scale_type):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ja/aspose.slides/slidesizetype) | 適用する事前定義されたスライドサイズ。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype) | 使用するコンテンツのスケーリングモード。 |

### 備考

[`SlideSizeType.CUSTOM`](/slides/python-net/ja/aspose.slides/slidesizetype/CUSTOM) 以外の任意の値を割り当てると、選択したタイプに基づいて [`SlideSize.size`](/slides/python-net/ja/aspose.slides/slidesize/size) が調整され、[`SlideSize.orientation`](/slides/python-net/ja/aspose.slides/slidesize/orientation) が保持されます。


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
幅と高さを明示的に設定し、既存のコンテンツをスケーリングします。


```python
def set_size(self, width, height, scale_type):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| width | **float** | ポイント単位の新しいスライドの幅。 |
| height | **float** | ポイント単位の新しいスライドの高さ。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype) | 使用するコンテンツのスケーリングモード。 |

### 備考

この操作は [`SlideSize.type`](/slides/python-net/ja/aspose.slides/slidesize/type) プロパティを [`SlideSizeType.CUSTOM`](/slides/python-net/ja/aspose.slides/slidesizetype/CUSTOM) にリセットし、[`SlideSize.orientation`](/slides/python-net/ja/aspose.slides/slidesize/orientation) を設定します。


### 参照
* クラス [`SlideSize`](/slides/python-net/ja/aspose.slides/slidesize)
* 列挙型 [`SlideSizeScaleType`](/slides/python-net/ja/aspose.slides/slidesizescaletype)
* 列挙型 [`SlideSizeType`](/slides/python-net/ja/aspose.slides/slidesizetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)