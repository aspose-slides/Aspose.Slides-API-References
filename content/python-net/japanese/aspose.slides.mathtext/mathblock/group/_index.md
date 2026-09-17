---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathblock/group/
weight: 130
---
## group(self) {#}
この要素を下部の波括弧を使用してグループ化します

### 戻り値

新しい型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) のインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下部の波括弧などのグループ化文字またはその他の文字を使用してグループ化します

### 戻り値

新しい型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) のインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | 下部の波括弧 (U+23DF) などのグループ化文字、またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ化文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            たとえば、グループ文字がオブジェクトの上にある場合、<br/><br/>            VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを示します。<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |



### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock)
* 列挙体 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)