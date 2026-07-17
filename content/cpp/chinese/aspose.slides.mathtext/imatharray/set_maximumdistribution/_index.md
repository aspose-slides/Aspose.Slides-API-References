---
title: set_MaximumDistribution()
second_title: Aspose.Slides for C++ API 参考
description: 最大分布 当为 true 时，数组会按照包含元素（页面、列、单元格等）的最大宽度进行间距设置。
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imatharray/set_maximumdistribution/
---
## IMathArray::set_MaximumDistribution(bool) 方法

最大分布：当为 true 时，数组会按包含元素（页面、列、单元格等）的最大宽度进行间距设置。

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_MaximumDistribution(bool value)=0
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