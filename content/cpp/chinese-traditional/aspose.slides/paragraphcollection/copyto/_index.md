---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 105
url: /zh-hant/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) 方法

將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | 從 [ICollection](../../../system.collections.generic/icollection/) 複製的元素之目的地為單維 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必須使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中開始複製的零基索引。 |

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IParagraph](../../iparagraph/)
* 類別 [ParagraphCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)