---
title: get_ObjectDistribution()
second_title: Aspose.Slides for C++ API 参考
description: 对象分布：当为 true 时，数组的内容会按数组对象的最大宽度进行间隔。
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imatharray/get_objectdistribution/
---
## IMathArray::get_ObjectDistribution() 方法

对象分布 当为 true 时，数组的内容会间隔到数组对象的最大宽度。

```cpp
virtual bool Aspose::Slides::MathText::IMathArray::get_ObjectDistribution()=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 另请参见

* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)