---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 326
url: /zh-hant/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) 方法

將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | 一維的 [System::Array](../../../system/array/)，作為從 [ICollection](../../../system.collections.generic/icollection/) 複製過來的元素的目的地。[System::Array](../../../system/array/) 必須使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中開始複製的零基索引。 |

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImageTransformOperation](../../iimagetransformoperation/)
* 類別 [ImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* 程式庫 [Aspose.Slides](../../../)