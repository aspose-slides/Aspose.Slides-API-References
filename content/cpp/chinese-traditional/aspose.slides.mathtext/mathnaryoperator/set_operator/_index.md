---
title: set_Operator()
second_title: Aspose.Slides for C++ API 參考文件
description: "Nary 運算子字元 例如：'\\u2211'，'\\u222B'"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) method


Nary 運算子字元 例如：'\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## 備註


範例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 另請參閱

* 類別 [MathNaryOperator](../)
* 名稱空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)