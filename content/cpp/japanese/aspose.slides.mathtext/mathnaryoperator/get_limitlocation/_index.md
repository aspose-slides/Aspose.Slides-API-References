---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API リファレンス
description: リミットの位置（下付き文字と上付き文字）
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() メソッド

リミットの位置 (下付き文字 と 上付き文字)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
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