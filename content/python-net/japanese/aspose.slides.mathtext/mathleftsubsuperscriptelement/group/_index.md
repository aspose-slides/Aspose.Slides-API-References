---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
この要素を下向き波括弧を使用してグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を、下向き波括弧などのグループ化文字を使用してグループ化します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグループ化文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ化文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            例として、グループ文字がオブジェクトの上にある場合、<br/><br/>            VerticalJustification of Top はオブジェクトの上部がベースライン上にあることを示します。;<br/><br/>            VerticalJustification が Bottom に設定された場合、オブジェクトの底部がベースライン上にあります |



### 参照
* class [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathLeftSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)