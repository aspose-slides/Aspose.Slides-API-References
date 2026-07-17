---
title: get_MaximumDistribution()
second_title: Aspose.Slides for C++ API 参考
description: Maximum Distribution 为 true 时，数组会根据包含元素（页面、列、单元格等）的最大宽度进行间隔。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imatharray/get_maximumdistribution/
---
## IMathArray::get_MaximumDistribution() 方法

Maximum Distribution 为 true 时，数组会根据包含元素（页、列、单元格等）的最大宽度进行间隔。

```cpp
virtual bool Aspose::Slides::MathText::IMathArray::get_MaximumDistribution()=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 另请参阅

* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)