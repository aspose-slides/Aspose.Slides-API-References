---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides C++ API 参考
description: 创建数学分组字符
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method


创建数学分组字符

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用分组字符的数学元素 |
| character | char16_t | 分组字符 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分组字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 垂直对齐方式 |

### 返回值

新分组字符元素

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method


创建数学分组字符

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用分组字符的数学元素 |

### 返回值

新分组字符元素

## 参见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathGroupingCharacterFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)