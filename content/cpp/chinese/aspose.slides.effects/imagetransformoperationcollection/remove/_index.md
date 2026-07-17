---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从 ICollection 中移除特定对象的第一次出现。
type: docs
weight: 339
url: /zh/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation>&) 方法

从 [ICollection](../../../system.collections.generic/icollection/) 中移除特定对象的第一次出现。

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)<[IImageTransformOperation](../../iimagetransformoperation/)>& | 要从 [ICollection](../../../system.collections.generic/icollection/) 中移除的对象。 |

### 返回值

如果成功从 [ICollection](../../../system.collections.generic/icollection/) 中移除 *item*，则返回 true；否则返回 false。此方法也在原始 [ICollection](../../../system.collections.generic/icollection/) 中未找到 *item* 时返回 false。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IImageTransformOperation](../../iimagetransformoperation/)
* 类 [ImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)