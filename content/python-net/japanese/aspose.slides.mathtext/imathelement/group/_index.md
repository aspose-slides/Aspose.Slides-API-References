---
title: group method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
この要素を下側の波かっこを使用してグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下側の波かっこやその他の文字などのグルーピング文字を使用してグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | グルーピング文字として BOTTOM CURLY BRACKET (U+23DF) またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直配置。<br/><br/>オブジェクトのベースラインに対する整列を指定します。<br/><br/>たとえば、グループ文字がオブジェクトの上にある場合、<br/><br/>VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを示します。<br/><br/>VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |



### 参照
* クラス [`IMathElement`](/slides/python-net/ja/aspose.slides.mathtext/imathelement)
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* 列挙 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)