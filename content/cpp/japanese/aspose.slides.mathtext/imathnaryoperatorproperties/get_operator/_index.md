---
title: get_Operator()
second_title: Aspose.Slides for C++ API リファレンス
description: "Nary 演算子文字 例: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() メソッド


Nary 演算子文字 例: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 参照

* クラス [IMathNaryOperatorProperties](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)