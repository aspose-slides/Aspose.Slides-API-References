---
title: Collect
second_title: Aspose.Slides for C++ API 参考
description: 表示一个用于从 Presentation 收集不同类型模型对象的方法组。
type: docs
weight: 1
url: /zh/aspose.slides.lowcode/collect/
---
## Collect 类

表示一个用于从 [Presentation](../../aspose.slides/presentation/) 收集不同类型模型对象的方法组。

```cpp
class Collect
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 收集 [Presentation](../../aspose.slides/presentation/) 中的所有 [Shape](../../aspose.slides/shape/) 实例。 |
## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... 更改形状格式或其他属性
}
```

## 另请参见

* 命名空间 [Aspose::Slides::LowCode](../)
* 库 [Aspose.Slides](../../)