---
title: Group
second_title: Aspose.Sildes for .NET API Reference
description: 使用下方的大括号将此元素放入一个组中
type: docs
weight: 60
url: /zh/aspose.slides.mathtext/mathelementbase/group/
---

## Group() {#group}

使用下方的大括号将此元素放入一个组中

```csharp
public IMathGroupingCharacter Group()
```

### Return Value

新实例类型为 [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Examples

示例:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### See Also

* interface [IMathGroupingCharacter](../../imathgroupingcharacter)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Group(char, MathTopBotPositions, MathTopBotPositions) {#group_1}

使用如下方大括号或其他分组字符将此元素放入一个组中

```csharp
public IMathGroupingCharacter Group(char character, MathTopBotPositions position, 
    MathTopBotPositions verticalJustification)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| character | Char | 分组字符，例如下方大括号 (U+23DF) 或任何其他字符 |
| position | MathTopBotPositions | 分组字符的位置 |
| verticalJustification | MathTopBotPositions | 分组字符的垂直对齐。指定对象与基线的对齐方式。例如，当分组字符在对象上方时，VerticalJustification 设置为 Top 表示对象的顶部落在基线上; 当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上 |

### Return Value

新实例类型为 [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Examples

示例:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group('\u23E1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

### See Also

* interface [IMathGroupingCharacter](../../imathgroupingcharacter)
* enum [MathTopBotPositions](../../mathtopbotpositions)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->