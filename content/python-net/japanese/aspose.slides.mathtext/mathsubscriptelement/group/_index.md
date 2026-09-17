---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
この要素を下向きの波かっこ（bottom curly bracket）を使用してグループに配置します

### 戻り値

新しい [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) 型のインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を、下向き波かっこなどのグルーピング文字を使用してグループに配置します

### 戻り値

新しい [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) 型のインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字、またはその他任意の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直位置揃え。<br/><br/>オブジェクトのベースラインに対する配置を指定します。<br/><br/>例えば、グループ文字がオブジェクトの上にある場合、<br/><br/>VerticalJustification が Top の場合はオブジェクトの上部がベースライン上に来ることを示します。<br/><br/>VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上に来ます |



### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathSubscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathsubscriptelement)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)