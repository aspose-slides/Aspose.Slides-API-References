---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並傳回包含所有投影片的陣列。
type: docs
weight: 92
url: /zh-hant/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() method

建立並返回包含所有投影片的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### 傳回值

[ISlide](../../islide/) 的陣列

## ISlideCollection::ToArray(int32_t, int32_t) method

建立並返回包含指定範圍內所有投影片的陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 要新增之第一張投影片的索引。 |
| count | **int32_t** | 要新增的投影片數量。 |

### 傳回值

[ISlide](../../islide/) 的陣列

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [ISlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)