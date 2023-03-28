---
title: CachedEnumerable()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 1
url: /cpp/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable([System::Func](../../../system/func/)\<**bool**\>) constructor




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | callback which is called when next item is needed. callback should use Add method to insert next item of return false when no more items |

## See Also

* Class [Func](../../../system/func/)
* Class [CachedEnumerable](../)
* Namespace [System::Linq::Details](../../)
* Library [Aspose.Slides](../../../)
