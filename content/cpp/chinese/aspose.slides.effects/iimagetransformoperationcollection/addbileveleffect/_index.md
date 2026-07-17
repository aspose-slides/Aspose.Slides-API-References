---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API 参考
description: 将新的 Bi-Level（黑/白）效果添加到集合的末尾。
type: docs
weight: 118
url: /zh/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) 方法

将新的 Bi-Level（黑/白）效果添加到集合的末尾。

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | **float** | Bi-Level 效果的亮度阈值。大于或等于阈值的值设置为白色。小于阈值的值设置为黑色。 |

### 返回值

集合中新图像效果的索引。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBiLevel](../../ibilevel/)
* 类 [IImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)