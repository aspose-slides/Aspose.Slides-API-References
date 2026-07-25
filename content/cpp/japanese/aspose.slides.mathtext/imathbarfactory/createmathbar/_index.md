---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素にバーを適用して数式バーを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) メソッド

要素にバーを適用して数式バーを作成します

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーを適用する数式要素 |

### 戻り値

新しい数式バー要素

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) メソッド

要素にバーを適用して数式バーを作成します

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーを適用する数式要素 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | バーの位置 |

### 戻り値

新しい数式バー要素

## 参照

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)