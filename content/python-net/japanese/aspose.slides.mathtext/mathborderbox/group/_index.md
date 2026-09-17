---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
この要素を下部の波括弧を使用してグループに配置します

### 返り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を、bottom curly bracket などのグルーピング文字または他の文字を使用してグループに配置します

### 返り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字、またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>オブジェクトのベースラインに対する配置を指定します。<br/><br/>たとえば、グループ文字がオブジェクトの上にある場合、<br/><br/>VerticalJustification が Top の場合、オブジェクトの上部がベースライン上に位置することを意味します。<br/><br/>VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上に位置します |



### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathBorderBox`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)