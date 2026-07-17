---
title: CreateMathBar()
second_title: Aspose.Slides C++ API 参考
description: 通过对元素应用创建数学 bar
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) 方法

通过对元素应用创建数学 bar

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用 bar 的数学元素 |

### 返回值

新的数学 bar 元素

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) 方法

通过对元素应用创建数学 bar

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用 bar 的数学元素 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | bar 的位置 |

### 返回值

新的数学 bar 元素

## 另见

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBar](../../imathbar/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathBarFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)