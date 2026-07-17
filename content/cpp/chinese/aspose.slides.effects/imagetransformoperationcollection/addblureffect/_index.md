---
title: AddBlurEffect()
second_title: Aspose.Slides C++ API 参考
description: 将新的模糊效果添加到集合的末尾。
type: docs
weight: 157
url: /zh/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) 方法

将新的[Blur](../../blur/)效果添加到集合的末尾。

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | **double** | 模糊的半径。 |
| grow | **bool** | 指定对象的边界是否应因模糊而增大。True 表示边界会增大，false 表示不会增大。 |

### 返回值

集合中新图像效果的索引。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBlur](../../iblur/)
* 类 [ImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)