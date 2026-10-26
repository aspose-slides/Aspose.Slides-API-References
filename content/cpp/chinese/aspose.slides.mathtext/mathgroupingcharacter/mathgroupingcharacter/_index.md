---
title: MathGroupingCharacter()
second_title: Aspose.Slides C++ API 参考
description: 使用默认分组字符 U+23DF（底部大括号）初始化 MathGroupingCharacter 类的新实例
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) 构造函数


使用默认分组字符 U+23DF（底部大括号）初始化 [MathGroupingCharacter](../) 类的新实例

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 应用于该条的基元素 |
## 备注



示例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 构造函数


初始化 [MathGroupingCharacter](../) 类的新实例。

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 应用于该条的基元素 |
| character | char16_t | 分组字符 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的垂直对齐方式 |
## 备注



示例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## 另请参见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)