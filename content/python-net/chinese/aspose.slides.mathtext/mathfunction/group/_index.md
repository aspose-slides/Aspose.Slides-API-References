---
title: group method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
将此元素使用底部大括号放入组中

### 返回

新实例，类型为 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
将此元素使用分组字符（例如底部大括号或其他字符）放入组中

### 返回

新实例，类型为 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| character | **char** | 分组字符，例如底部大括号 (U+23DF) 或任何其他 |
| position | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 分组字符的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 分组字符的垂直对齐。<br/><br/>            指定对象相对于基线的对齐方式。<br/><br/>            例如，当分组字符位于对象之上时， <br/><br/>            VerticalJustification of Top 表示对象的顶部位于基线上；<br/><br/>            当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上 |



### 另请参见
* 类 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)
* 类 [`MathFunction`](/slides/python-net/zh/aspose.slides.mathtext/mathfunction)
* 枚举 [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)