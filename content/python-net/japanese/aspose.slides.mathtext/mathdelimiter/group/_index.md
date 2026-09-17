---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
この要素を下側の波かっこを使用してグループに配置します

### Returns
型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下側の波かっこなどのグルーピング文字を使用してグループに配置します

### Returns
型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス

```python
def group(self, character, position, vertical_justification):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            例えば、グループ文字がオブジェクトの上にある場合、<br/><br/>            Top の VerticalJustification はオブジェクトの上部がベースライン上にあることを意味します；<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |

### See Also
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter)
* 列挙 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)