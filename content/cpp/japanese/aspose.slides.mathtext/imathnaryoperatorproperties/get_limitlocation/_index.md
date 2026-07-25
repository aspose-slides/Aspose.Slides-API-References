---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API リファレンス
description: 制限（下付きと上付き）の位置
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() メソッド

制限（下付きと上付き）の位置

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## 備考

例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 関連項目

* Enum [MathLimitLocations](../../mathlimitlocations/)
* クラス [IMathNaryOperatorProperties](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)