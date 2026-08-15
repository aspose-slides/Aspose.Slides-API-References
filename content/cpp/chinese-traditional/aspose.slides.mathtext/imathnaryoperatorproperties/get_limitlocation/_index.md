---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API 參考
description: 限制（下標與上標）的位置
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() 方法


The location of limits (subscript and superscript)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## 備註


範例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 另請參閱

* 列舉 [MathLimitLocations](../../mathlimitlocations/)
* 類別 [IMathNaryOperatorProperties](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)