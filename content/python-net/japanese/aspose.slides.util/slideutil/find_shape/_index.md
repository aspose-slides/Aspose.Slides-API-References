---
title: find_shape method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
PPTXプレゼンテーション内で代替テキストによりシェイプを検索します。

### 戻り値

Shape または None。



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| alt_text | **str** | シェイプの代替テキスト。 |


## find_shape(slide, alt_text) {#ibaseslide-str}
PPTXプレゼンテーションのスライド上で代替テキストによりシェイプを検索します。

### 戻り値

Shape または None。



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | スキャンされたスライド。 |
| alt_text | **str** | シェイプの代替テキスト。 |



### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`SlideUtil`](/slides/python-net/ja/aspose.slides.util/slideutil)
* モジュール [`aspose.slides.util`](/slides/python-net/ja/aspose.slides.util)
* ライブラリ [`Aspose.Slides`](/slides/python-net)