---
title: Group()
second_title: Aspose.Slides C++ API 参考
description: 使用底部大括号将此元素放入组中
type: docs
weight: 248
url: /zh/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() 方法


使用底部大括号将此元素放入组中

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### 返回值

类型为 [IMathGroupingCharacter](../../imathgroupingcharacter/) 的新实例
## 备注



示例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) 方法


使用分组字符（例如底部大括号或其他）将此元素放入组中

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | 分组字符，例如底部大括号 (U+23DF) 或其他 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | group character 的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部落在基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上 |

### 返回值

类型为 [IMathGroupingCharacter](../../imathgroupingcharacter/) 的新实例
## 备注



示例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 另请参见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)