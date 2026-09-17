---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
この要素を下部の波かっこを使用してグループに配置します

### 戻り値

[`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) 型の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を、bottom curly bracket やその他のグループ化文字を使用してグループに配置します

### 戻り値

[`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) 型の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグループ化文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ化文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>            オブジェクトのベースラインに対する整列を指定します。<br/><br/>            例として、グループ文字がオブジェクトの上にある場合、<br/><br/>            Top の VerticalJustification はオブジェクトの上端がベースライン上にあることを示します。<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下端がベースライン上にあります。 |



### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathRightSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)