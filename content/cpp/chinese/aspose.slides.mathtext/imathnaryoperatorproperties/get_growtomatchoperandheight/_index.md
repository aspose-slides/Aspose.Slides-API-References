---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 参考
description: 运算符字符在垂直方向上增长以匹配其操作数的高度
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() 方法

运算符字符在垂直方向上增长以匹配其操作数的高度

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## 备注

示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 另见

* 类 [IMathNaryOperatorProperties](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)