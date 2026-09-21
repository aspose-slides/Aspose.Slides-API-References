---
title: group method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathematicaltext/group/
weight: 80
---
## group(self) {#}
將此元素放入使用底部大括號的群組中

### 回傳

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
將此元素放入使用群組字元（例如底部大括號或其他）的群組中

### 回傳

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| character | **char** | 分組字元，例如 BOTTOM CURLY BRACKET (U+23DF) 或其他任何字元 |
| position | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 分組字元的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 群組字元的垂直對齊方式。<br/><br/>指定物件相對於基線的對齊方式。<br/><br/>例如，當群組字元位於物件之上時，<br/><br/>VerticalJustification 為 Top 表示物件的頂部位於基線上；<br/><br/>當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上 |



### 另請參閱
* class [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathematicalText`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext)
* enumeration [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)