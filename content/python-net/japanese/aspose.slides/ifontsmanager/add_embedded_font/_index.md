---
title: add_embedded_font method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/add_embedded_font/
weight: 10
---
## add_embedded_font(self, font_data, embed_font_rule) {#ifontdata-asposeslidesexportembedfontcharacters}
埋め込みフォントを追加します。
フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるかを検証してください。フォントデータが None の場合、またはこのフォントがすでに埋め込まれている場合、ArgumentException がスローされる可能性があります。


```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) | フォントデータ オブジェクト [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/ja/aspose.slides.export/embedfontcharacters) | 埋め込みフォント ルール [`EmbedFontCharacters`](/slides/python-net/ja/aspose.slides.export/embedfontcharacters) |


## add_embedded_font(self, font_data, embed_font_rule) {#bytes-asposeslidesexportembedfontcharacters}
埋め込みフォントを追加します。
フォントを追加する際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるかを検証してください。フォントデータが None の場合、またはこのフォントがすでに埋め込まれている場合、ArgumentException がスローされる可能性があります。


```python
def add_embedded_font(self, font_data, embed_font_rule):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_data | **bytes** | フォントデータ **int**[] |
| embed_font_rule | [`EmbedFontCharacters`](/slides/python-net/ja/aspose.slides.export/embedfontcharacters) | 埋め込みフォント ルール [`EmbedFontCharacters`](/slides/python-net/ja/aspose.slides.export/embedfontcharacters) |



### 参照
* 列挙 [`EmbedFontCharacters`](/slides/python-net/ja/aspose.slides.export/embedfontcharacters)
* クラス [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata)
* クラス [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)