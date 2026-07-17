---
title: set_ObjectDistribution()
second_title: Aspose.Slides for C++ API 参考
description: 对象分布：当为 true 时，数组的内容会按数组对象的最大宽度进行间距调整。
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/matharray/set_objectdistribution/
---
## MathArray::set_ObjectDistribution(bool) 方法

对象分布 当为 true 时，数组的内容会按数组对象的最大宽度进行间距调整。

```cpp
void Aspose::Slides::MathText::MathArray::set_ObjectDistribution(bool value) override
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 另请参见

* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)