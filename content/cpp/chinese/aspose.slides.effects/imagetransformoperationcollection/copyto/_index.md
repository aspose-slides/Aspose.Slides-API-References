---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: "将 ICollection 的元素复制到 System::Array 中，从特定的 System::Array 索引开始。"
type: docs
weight: 326
url: /zh/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) 方法


将 [ICollection](../../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | 一维 [System::Array](../../../system/array/)，是从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标。[System::Array](../../../system/array/) 必须使用零基索引。 |
| arrayIndex | **int32_t** | *array* 中的零基索引，表示复制开始的位置。 |

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImageTransformOperation](../../iimagetransformoperation/)
* 类 [ImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)