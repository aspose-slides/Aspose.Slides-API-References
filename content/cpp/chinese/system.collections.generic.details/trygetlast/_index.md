---
title: TryGetLast()
second_title: Aspose.Slides C++ API 参考
description: 尝试获取集合的最后一个元素。
type: docs
weight: 261
url: /zh/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) 函数


尝试获取集合的最后一个元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合元素的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要获取元素的集合。 |
| found | **bool**\& | 输出参数。当集合包含任何元素时返回 true，否则返回 false。 |

### 返回值

返回集合的最后一个元素。当集合为空时返回该类型的默认值。

## 另见

* 类 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)