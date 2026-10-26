---
title: CreateMathBar()
second_title: Aspose.Slides C++ API 參考手冊
description: 透過套用於元素來建立數學橫線
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) 方法

透過套用於元素來建立數學橫線

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要套用橫線的數學元素 |

### 回傳值

新的數學橫線元素

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) 方法

透過套用於元素來建立數學橫線

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要套用橫線的數學元素 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 橫線的位置 |

### 回傳值

新的數學橫線元素

## 另見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBar](../../imathbar/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBarFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)