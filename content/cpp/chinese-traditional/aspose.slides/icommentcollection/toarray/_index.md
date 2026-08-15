---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考
description: 建立並回傳包含所有評論的陣列。
type: docs
weight: 66
url: /zh-hant/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() 方法

建立並回傳包含所有評論的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### 回傳值

[IComment](../../icomment/) 陣列。

## ICommentCollection::ToArray(int32_t, int32_t) 方法

建立並回傳指定範圍內所有評論的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 要回傳的首個評論的索引。 |
| count | **int32_t** | 要回傳的評論數量。 |

### 回傳值

[IComment](../../icomment/) 陣列。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)