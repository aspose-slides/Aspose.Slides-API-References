---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考文件
description: 運算子字元會垂直增長以匹配其運算元的高度
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() 方法

運算子字元會垂直增長以匹配其運算元的高度

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## 備註

範例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 參見

* 類別 [IMathNaryOperatorProperties](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)