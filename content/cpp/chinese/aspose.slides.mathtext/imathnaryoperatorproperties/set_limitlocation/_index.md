---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API 参考
description: 限制的位置（下标和上标）
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) 方法

限制的位置（下标和上标）

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## 备注

示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## 另见

* 枚举 [MathLimitLocations](../../mathlimitlocations/)
* 类 [IMathNaryOperatorProperties](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)