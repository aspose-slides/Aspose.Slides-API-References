---
title: get_ObjectDistribution()
second_title: Aspose.Slides for C++ API 参考
description: 对象分布 当为 true 时，数组的内容将按数组对象的最大宽度进行间距。
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/matharray/get_objectdistribution/
---
## MathArray::get_ObjectDistribution() 方法


对象分布 当为 true 时，数组的内容将按数组对象的最大宽度进行间距。

```cpp
bool Aspose::Slides::MathText::MathArray::get_ObjectDistribution() override
```

## 备注


示例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 另见

* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)