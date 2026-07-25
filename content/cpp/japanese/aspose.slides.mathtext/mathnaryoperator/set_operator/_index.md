---
title: set_Operator()
second_title: C++ 用 Aspose.Slides API リファレンス
description: "Nary Operator 文字 例: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) メソッド

Nary Operator文字 例: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## 備考

例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 参照

* クラス [MathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)