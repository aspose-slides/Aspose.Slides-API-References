---
title: CachedEnumerable()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 1
url: /zh/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) 构造函数




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | 在需要下一个项时调用的回调。回调应使用 Add 方法插入下一个项，若没有更多项则返回 false |

## 另见

* 类 [Func](../../../system/func/)
* 类 [CachedEnumerable](../)
* 命名空间 [System::Linq::Details](../../)
* 库 [Aspose.Slides](../../../)