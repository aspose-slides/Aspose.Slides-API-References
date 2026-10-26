---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
この要素を下カール括弧を使用してグループに配置します

### 戻り値

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
下カール括弧などのグループ化文字を使用してこの要素をグループに配置します

### 戻り値

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| character | **char** | 下カール括弧 (U+23DF) などのグループ化文字またはその他の文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ化文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            例えば、グループ文字がオブジェクトの上にある場合、<br/><br/>            Top の VerticalJustification はオブジェクトの上部がベースライン上にあることを意味します;<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |



### 関連項目
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom)
* 列挙体 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)