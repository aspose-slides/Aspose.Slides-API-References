---
title: get_Operator()
second_title: Aspose.Slides C++ API 參考
description: "Nary 運算子字元，例如: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() 方法


Nary 運算子字元，例如： '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## 備註


範例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 另請參閱

* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)