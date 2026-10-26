---
title: Group()
second_title: Aspose.Slides C++ API 参考
description: 使用底部大括号将此元素放入组中
type: docs
weight: 235
url: /zh/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() method


使用底部大括号将此元素放入组中

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### 返回值

类型 [IMathGroupingCharacter](../../imathgroupingcharacter/) 的新实例
## 备注



示例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) method


使用分组字符（例如底部大括号或其他字符）将此元素放入组中

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| character | char16_t | 分组字符，例如 BOTTOM CURLY BRACKET (U+23DF) 或任何其他 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上 |

### 返回值

类型 [IMathGroupingCharacter](../../imathgroupingcharacter/) 的新实例
## 备注



示例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 另见

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)