---
title: AddBiLevelEffect()
second_title: Aspose.Slides C++ API 参考
description: 在集合的末尾添加新的双层（黑/白）效果。
type: docs
weight: 144
url: /zh/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) 方法


在集合的末尾添加新的双层（黑/白）效果。

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | **float** | Bi-Level 效果的亮度阈值。大于或等于阈值的值将设为白色。小于阈值的值将设为黑色。 |

### 返回值

集合中新图像效果的索引。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBiLevel](../../ibilevel/)
* 类 [ImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)