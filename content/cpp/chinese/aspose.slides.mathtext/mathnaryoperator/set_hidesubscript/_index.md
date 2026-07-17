---
title: set_HideSubscript()
second_title: Aspose.Slides C++ API 参考
description: 隐藏下标
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/mathnaryoperator/set_hidesubscript/
---
## MathNaryOperator::set_HideSubscript(bool) 方法


隐藏下标

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSubscript(bool value) override
```

## 备注


示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 另见

* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)