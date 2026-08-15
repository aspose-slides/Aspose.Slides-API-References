---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 傳回集合中指定投影片的索引。
type: docs
weight: 118
url: /zh-hant/aspose.slides/islidecollection/indexof/
---
## ISlideCollection::IndexOf(System::SharedPtr\<ISlide\>) 方法


傳回集合中指定的投影片的索引。

```cpp
virtual int32_t Aspose::Slides::ISlideCollection::IndexOf(System::SharedPtr<ISlide> slide)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要搜尋的。 |

### 回傳值

投影片的索引，若投影片不屬於此集合則為 -1。

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [ISlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)