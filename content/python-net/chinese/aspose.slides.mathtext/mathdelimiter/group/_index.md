---
title: group method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
使用底部花括号将此元素放入组中

### 返回
New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
使用分组字符（例如底部花括号或其他字符）将此元素放入组中

### 返回
New instance of type [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| character | **char** | 分组字符，例如底部花括号 (U+23DF) 或任何其他字符 |
| position | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 分组字符的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 组字符的垂直对齐方式。<br/><br/>            指定对象相对于基线的对齐方式。<br/><br/>            例如，当组字符位于对象上方时，<br/><br/>            垂直对齐方式为 Top 表示对象的顶部位于基线上；<br/><br/>            当垂直对齐方式设置为 Bottom 时，对象的底部位于基线上 |

### 另请参见
* class [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathDelimiter`](/slides/python-net/zh/aspose.slides.mathtext/mathdelimiter)
* enumeration [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)