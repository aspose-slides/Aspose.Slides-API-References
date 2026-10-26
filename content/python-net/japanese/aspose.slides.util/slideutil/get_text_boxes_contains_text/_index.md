---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
指定されたスライド上で、指定されたテキストを含むすべてのテキスト フレームを返します。

### 戻り値

指定されたテキストを含む [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe) オブジェクトの配列です。

```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 検索対象のスライドです。 |
| text | **str** | テキスト フレーム内で検索するテキストです。 |
| check_placeholder_text | **bool** | 空のテキスト フレームであっても、プレースホルダー テキストに検索テキストが含まれている場合に含めるかどうかを示します。 |

### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe)
* クラス [`SlideUtil`](/slides/python-net/ja/aspose.slides.util/slideutil)
* モジュール [`aspose.slides.util`](/slides/python-net/ja/aspose.slides.util)
* ライブラリ [`Aspose.Slides`](/slides/python-net)