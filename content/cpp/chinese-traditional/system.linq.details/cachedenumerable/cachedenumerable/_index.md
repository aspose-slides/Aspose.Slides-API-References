---
title: CachedEnumerable()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 1
url: /zh-hant/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) 建構函式




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | 在需要下一個項目時會被呼叫的回呼。回呼應該使用 Add 方法插入下一個項目，若沒有更多項目則回傳 false |

## 另請參閱

* 類別 [Func](../../../system/func/)
* 類別 [CachedEnumerable](../)
* 命名空間 [System::Linq::Details](../../)
* 函式庫 [Aspose.Slides](../../../)