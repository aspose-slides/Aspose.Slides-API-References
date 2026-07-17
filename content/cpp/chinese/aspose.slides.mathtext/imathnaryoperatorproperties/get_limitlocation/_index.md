---
title: get_LimitLocation()
second_title: Aspose.Slides C++ API 参考
description: 限制的位置（下标和上标）
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() 方法

限制的位置（下标和上标）

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## 备注

示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 另请参阅

* 枚举 [MathLimitLocations](../../mathlimitlocations/)
* 类 [IMathNaryOperatorProperties](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)