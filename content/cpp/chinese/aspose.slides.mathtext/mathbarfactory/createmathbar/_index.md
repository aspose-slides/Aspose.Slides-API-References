---
title: CreateMathBar()
second_title: Aspose.Slides C++ API 参考
description: 通过对元素应用创建数学上标
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) method


通过应用于该元素创建一个数学上标

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用上标的数学元素 |

### 返回值

新的数学上标元素

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) method


通过应用于该元素创建一个数学上标

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用上标的数学元素 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 上标的位置 |

### 返回值

新的数学上标元素

## 另见

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../../imathelement/)
* Class [MathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)