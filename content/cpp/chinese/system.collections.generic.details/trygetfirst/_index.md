---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API参考
description: 尝试获取集合的第一个元素。
type: docs
weight: 248
url: /zh/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) 函数


尝试获取集合的第一个元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合元素的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要获取元素的集合。 |
| found | **bool**\& | 输出参数。当集合中包含任何元素时返回 true。否则返回 false。 |

### 返回值

返回集合的第一个元素。当集合为空时返回该类型的默认值。

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) 函数


尝试获取集合中满足谓词函数的第一个元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合元素的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要获取元素的集合。 |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | 谓词函数。 |
| found | **bool**\& | 输出参数。当集合中包含任何元素时返回 true。否则返回 false。 |

### 返回值

返回集合的第一个元素。如果未找到满足指定谓词函数的元素，则返回该类型的默认值。

## 另请参阅

* 类 [IEnumerable](../../system.collections.generic/ienumerable/)
* 类 [Func](../../system/func/)
* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)