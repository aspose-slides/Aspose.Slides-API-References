---
title: get_Operator()
second_title: Aspose.Slides for C++ API 参考
description: "Nary 运算符字符 例如： '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() 方法


Nary 运算符字符 例如： '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## 备注


示例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## 另请参阅

* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)