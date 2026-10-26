---
title: set_ObjectDistribution()
second_title: Aspose.Slides for C++ API 参考
description: 对象分布 当为 true 时，数组的内容会根据数组对象的最大宽度进行间隔排列。
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imatharray/set_objectdistribution/
---
## IMathArray::set_ObjectDistribution(bool) 方法

对象分布 当为 true 时，数组的内容会根据数组对象的最大宽度进行间隔排列。

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_ObjectDistribution(bool value)=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 另见

* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)