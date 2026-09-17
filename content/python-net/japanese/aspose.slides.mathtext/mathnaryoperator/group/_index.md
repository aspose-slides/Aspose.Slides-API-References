---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
この要素を下部波括弧でグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下部波括弧やその他のグルーピング文字を使用してグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字、またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            例えば、グループ文字がオブジェクトの上にある場合、<br/><br/>            VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを意味します;<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |



### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathNaryOperator`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)