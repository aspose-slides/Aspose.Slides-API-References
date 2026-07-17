---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 参考
description: 操作符字符在垂直方向上增长以匹配其操作数的高度
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() 方法

操作符字符在垂直方向上增长以匹配其操作数的高度

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## 备注

示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 另请参见

* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)