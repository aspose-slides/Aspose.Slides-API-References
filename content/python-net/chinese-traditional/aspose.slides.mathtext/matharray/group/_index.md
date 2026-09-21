---
title: group method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
使用底部大括號將此元素放入一個群組

### 回傳

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
使用分組字元（例如底部大括號或其他）將此元素放入群組

### 回傳

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| character | **char** | 用於分組的字元，例如 BOTTOM CURLY BRACKET (U+23DF) 或其他任何字元 |
| position | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 分組字元的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | group字符的垂直對齊方式。<br/><br/>            指定物件相對於基線的對齊方式。<br/><br/>            例如，當分組字元位於物件之上時， <br/><br/>            VerticalJustification 為 Top 表示物件的頂部位於基線上；<br/><br/>            當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上 |



### 另請參閱
* 類別 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)
* 類別 [`MathArray`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray)
* 列舉 [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)