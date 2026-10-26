---
title: group method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
將此元素使用底部大括號放入群組

### 回傳

新實例類型 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
將此元素使用分組字元（例如底部大括號或其他）放入群組

### 回傳

新實例類型 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| character | **char** | 分組字元，例如底部大括號 (U+23DF) 或其他任何字元 |
| position | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | Position of grouping character |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | Group character 的垂直對齊方式。<br/><br/>指定物件相對於基線的對齊方式。<br/><br/>例如，當分組字元位於物件之上時，<br/><br/>VerticalJustification 設為 Top 表示物件的頂部位於基線上；<br/><br/>當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上 |



### 參見
* 類別 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)
* 類別 [`MathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom)
* 列舉 [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)