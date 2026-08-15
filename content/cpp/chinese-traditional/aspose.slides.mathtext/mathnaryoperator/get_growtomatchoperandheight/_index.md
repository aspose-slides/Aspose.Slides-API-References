---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考
description: 運算子字元垂直擴展以匹配其運算元高度
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() 方法

運算子字元垂直擴展以匹配其運算元高度

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## 備註

範例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 另請參閱

* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)