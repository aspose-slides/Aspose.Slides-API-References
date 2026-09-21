---
title: group method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
使用底部大括號將此元素放入群組中

### 回傳

新類型的實例 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
使用分組字元（例如底部大括號或其他字元）將此元素放入群組中

### 回傳

新類型的實例 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| character | **char** | 分組字元，例如底部大括號 (U+23DF) 或其他任何字元 |
| position | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 分組字元的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 群組字元的垂直對齊方式。<br/><br/>            指定物件相對於基線的對齊方式。<br/><br/>            例如，當群組字元位於物件之上時， <br/><br/>            將 VerticalJustification 設為 Top 表示物件的頂部位於基線上；<br/><br/>            當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上 |



### 另請參閱
* 類別 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)
* 類別 [`MathFunction`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction)
* 列舉 [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)