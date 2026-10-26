---
title: group method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathfraction/group/
weight: 80
---
## group(self) {#}
使用底部花括号将此元素放入组中

### 返回值

新实例，类型为 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
使用分组字符（例如底部花括号或其他字符）将此元素放入组中

### 返回值

新实例，类型为 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| character | **char** | 分组字符，例如底部花括号 (U+23DF) 或其他 |
| position | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 分组字符的位置 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions) | 组字符的垂直对齐方式。<br/><br/>            指定对象相对于基线的对齐方式。<br/><br/>            例如，当组字符位于对象上方时，<br/><br/>            VerticalJustification 为 Top 表示对象的顶部位于基线；<br/><br/>            当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线 |

### 另见
* 类 [`IMathGroupingCharacter`](/slides/python-net/zh/aspose.slides.mathtext/imathgroupingcharacter)
* 类 [`MathFraction`](/slides/python-net/zh/aspose.slides.mathtext/mathfraction)
* 枚举 [`MathTopBotPositions`](/slides/python-net/zh/aspose.slides.mathtext/mathtopbotpositions)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)