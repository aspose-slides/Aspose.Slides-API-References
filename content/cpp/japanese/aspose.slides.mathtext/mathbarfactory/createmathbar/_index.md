---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素にバーを適用して数式バーを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) メソッド

要素にバーを適用して数式バーを作成します

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーを適用する数式要素 |

### 戻り値

新しい数式バー要素

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) メソッド

要素にバーを適用して数式バーを作成します

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーを適用する数式要素 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | バーの位置 |

### 戻り値

新しい数式バー要素

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBar](../../imathbar/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBarFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)