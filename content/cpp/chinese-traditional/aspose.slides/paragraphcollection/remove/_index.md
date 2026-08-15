---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從 ICollection 中移除特定物件的第一個出現。
type: docs
weight: 131
url: /zh-hant/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) 方法


從 [ICollection](../../../system.collections.generic/icollection/) 中移除特定物件的第一個出現。

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要從 [ICollection](../../../system.collections.generic/icollection/) 中移除的物件。 |

### 傳回值

true if *item*  was successfully removed from the [ICollection](../../../system.collections.generic/icollection/); otherwise, false. This method also returns false if *item*  is not found in the original [ICollection](../../../system.collections.generic/icollection/).

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)