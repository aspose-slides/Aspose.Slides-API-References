---
title: get_Operator()
second_title: Aspose.Slides for C++ API 參考
description: "Nary 運算子字元 例如： '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() 方法


Nary 運算子字元 例如： '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## 備註


範例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 另請參閱

* 類別 [IMathNaryOperatorProperties](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)