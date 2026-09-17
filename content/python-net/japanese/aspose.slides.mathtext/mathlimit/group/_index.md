---
title: group method
second_title: Aspose.Slides for Python の .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
この要素を下の波かっこ (bottom curly bracket) を使用してグループ化します

### 戻り値

[`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下の波かっこや他の文字などのグルーピング文字を使用してグループ化します

### 戻り値

[`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グルーピング文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直方向の配置。<br/><br/>オブジェクトのベースラインに対する配置を指定します。<br/><br/>例えば、グループ文字がオブジェクトの上にある場合、<br/><br/>VerticalJustification が Top の場合はオブジェクトの上部がベースラインに一致し、<br/><br/>VerticalJustification が Bottom に設定されている場合はオブジェクトの下部がベースラインに合わせられます。 |



### 関連項目
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathLimit`](/slides/python-net/ja/aspose.slides.mathtext/mathlimit)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)