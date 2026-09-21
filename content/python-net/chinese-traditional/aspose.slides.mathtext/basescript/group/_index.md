---
title: group method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
將此元素以底部大括號的方式放入群組

### 返回

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
將此元素以分組字元（例如底部大括號或其他）放入群組

### 返回

New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| character | **char** | 分組字元，例如 BOTTOM CURLY BRACKET (U+23DF) 或其他 |
| position | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 分組字元的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions) | 群組字元的垂直對齊方式。<br/><br/>            指定物件相對於基線的對齊方式。<br/><br/>            例如，當群組字元位於物件上方時，<br/><br/>            垂直對齊設定為 Top 表示物件的頂部落在基線上；<br/><br/>            當垂直對齊設定為 Bottom 時，物件的底部位於基線上 |

### 另請參閱
* 類別 [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript)
* 類別 [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter)
* 列舉 [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)