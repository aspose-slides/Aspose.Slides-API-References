---
title: find_and_replace_text method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---
## find_and_replace_text(presentation, with_masters, find, replace, format) {#ipresentation-bool-str-str-portionformat}
指定された形式でプレゼンテーションのテキストを検索し、置換します

```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| with_masters | **bool** | マスタースライドをスキャンするかどうかを決定します。 |
| find | **str** | 検索する文字列値。 |
| replace | **str** | 置換する文字列値。 |
| format | [`PortionFormat`](/slides/python-net/ja/aspose.slides/portionformat) | テキスト部分を置換するための形式。None の場合、検索された文字列の最初の <br/><br/>            文字が使用されます。 |

### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`PortionFormat`](/slides/python-net/ja/aspose.slides/portionformat)
* クラス [`SlideUtil`](/slides/python-net/ja/aspose.slides.util/slideutil)
* モジュール [`aspose.slides.util`](/slides/python-net/ja/aspose.slides.util)
* ライブラリ [`Aspose.Slides`](/slides/python-net)