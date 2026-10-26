---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從 ICollection 中移除特定物件的首次出現。
type: docs
weight: 339
url: /zh-hant/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) 方法

移除第一個特定物件於 [ICollection](../../../system.collections.generic/icollection/) 中的出現。

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | 要從 [ICollection](../../../system.collections.generic/icollection/) 中移除的物件。 |

### 返回值

如果 *item* 成功從 [ICollection](../../../system.collections.generic/icollection/) 中移除則返回 true；否則返回 false。如果在原始 [ICollection](../../../system.collections.generic/icollection/) 中找不到 *item*，此方法也會返回 false。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImageTransformOperation](../../iimagetransformoperation/)
* 類別 [ImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* 函式庫 [Aspose.Slides](../../../)