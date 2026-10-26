---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考
description: 建立並傳回包含所有註解的陣列。
type: docs
weight: 105
url: /zh-hant/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() 方法


建立並傳回包含所有註解的陣列。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### 返回值

[Comment](../../comment/) 陣列。

## CommentCollection::ToArray(int32_t, int32_t) 方法


建立並傳回指定範圍內所有註解的陣列。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 要傳回的第一則註解的索引。 |
| count | **int32_t** | 要傳回的註解數量。 |

### 返回值

[Comment](../../comment/) 陣列。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [CommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)