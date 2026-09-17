---
title: group method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
この要素を下カールブラケットを使用してグループに配置します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
この要素を下カールブラケットやその他のグループ化文字を使用してグループに配置します

### 戻り値

型 [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter) の新しいインスタンス



```python
def group(self, character, position, vertical_justification):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| character | **char** | グループ化文字、たとえば下カールブラケット (U+23DF) またはその他 |
| position | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ化文字の位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions) | グループ文字の垂直配置。<br/><br/>            オブジェクトのベースラインに対する配置を指定します。<br/><br/>            たとえば、グループ文字がオブジェクトの上にある場合、<br/><br/>            VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを示します。<br/><br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります |

### 参照
* クラス [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter)
* クラス [`MathAccent`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent)
* 列挙型 [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)