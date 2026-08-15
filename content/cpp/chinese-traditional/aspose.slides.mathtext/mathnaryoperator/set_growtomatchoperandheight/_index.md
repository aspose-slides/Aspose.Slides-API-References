---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考
description: 運算子字元垂直增長以匹配其操作數的高度
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) 方法

運算子字元垂直增長以匹配其操作數的高度

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## 備註

範例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 另見

* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)