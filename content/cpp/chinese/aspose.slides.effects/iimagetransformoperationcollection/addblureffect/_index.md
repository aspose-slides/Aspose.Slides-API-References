---
title: AddBlurEffect()
second_title: Aspose.Slides C++ API 参考
description: 将新的 Blur 效果添加到集合的末尾。
type: docs
weight: 131
url: /zh/aspose.slides.effects/iimagetransformoperationcollection/addblureffect/
---
## IImageTransformOperationCollection::AddBlurEffect(double, bool) 方法


将新的 [Blur](../../blur/) 效果添加到集合的末尾。

```cpp
virtual System::SharedPtr<IBlur> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBlurEffect(double radius, bool grow)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | **double** | 模糊的半径。 |
| grow | **bool** | 指定对象的边界是否应因模糊而增大。True 表示边界被增大，false 表示未被增大。 |

### 返回值

集合中新图像效果的索引。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBlur](../../iblur/)
* 类 [IImageTransformOperationCollection](../)
* 命名空间 [Aspose::Slides::Effects](../../)
* 库 [Aspose.Slides](../../../)