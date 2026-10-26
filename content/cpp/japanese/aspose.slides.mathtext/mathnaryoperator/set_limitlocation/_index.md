---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字と上付き文字の位置
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) メソッド


制限（下付き文字と上付き文字）の位置

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## 備考


例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 参照

* 列挙体 [MathLimitLocations](../../mathlimitlocations/)
* クラス [MathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)