---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API 参考
description: 指定上限或下限
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) 方法

指定上限或下限

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## 备注

示例:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 另请参阅

* 类 [MathLimit](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)