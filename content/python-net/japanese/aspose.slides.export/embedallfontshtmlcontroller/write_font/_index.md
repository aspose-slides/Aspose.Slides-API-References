---
title: write_font method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/write_font/
weight: 50
---
## write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data) {#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes}
データを base64 として HTML ドキュメント自体に書き込みます


```python
def write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator) | HTML ジェネレータ |
| original_font | [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) | シリアライズされるフォント |
| substituted_font | [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) | 置換フォント（フォント置換が発生した場合）、それ以外は None |
| font_style | **str** | フォントスタイル |
| font_weight | **str** | フォントウェイト |
| font_data | **bytes** | フォントデータ |



### 参照
* クラス [`EmbedAllFontsHtmlController`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller)
* クラス [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata)
* クラス [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)