---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个数学分组字符
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 方法

创建一个数学分组字符

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用于应用分组字符的数学元素 |
| character | char16_t | 分组字符 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 垂直对齐 |

### 返回值

新的分组字符元素

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) 方法

创建一个数学分组字符

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用于应用分组字符的数学元素 |

### 返回值

新的分组字符元素

## 另请参见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathGroupingCharacterFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)