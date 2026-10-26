---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API 參考
description: 將新的 Bi-Level（黑/白）效果新增至集合的末端。
type: docs
weight: 144
url: /zh-hant/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) 方法

將新的 Bi-Level（黑/白）效果新增至集合的末端。

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| threshold | **float** | Bi-Level 效果的亮度閾值。大於或等於閾值的值會設為白色。小於閾值的值會設為黑色。 |

### 返回值

集合中新影像效果的索引。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBiLevel](../../ibilevel/)
* 類別 [ImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)