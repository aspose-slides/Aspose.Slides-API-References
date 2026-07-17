---
title: FindIndex()
second_title: Aspose.Slides C++ API 参考
description: 查找符合特定谓词的元素。
type: docs
weight: 404
url: /zh/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) 方法

查找符合特定谓词的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用于检查元素的谓词。 |

### 返回值

匹配元素的索引；如果未找到则返回 -1。

## List::FindIndex(int, System::Predicate\<T\>) 方法

查找符合特定谓词的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 开始搜索的索引。 |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用于检查元素的谓词。 |

### 返回值

匹配元素的索引；如果未找到则返回 -1。

## List::FindIndex(int, int, System::Predicate\<T\>) 方法

查找符合特定谓词的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 开始搜索的索引。 |
| count | int | 要遍历的元素数量。 |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用于检查元素的谓词。 |

### 返回值

匹配元素的索引；如果未找到则返回 -1。

## 另见

* Typedef [Predicate](../../../system/predicate/)
* 类 [List](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)