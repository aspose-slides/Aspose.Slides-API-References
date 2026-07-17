---
title: Find()
second_title: Aspose.Slides C++ API 参考
description: 在指定的数组中搜索满足指定谓词条件的第一个元素。
type: docs
weight: 651
url: /zh/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

在指定的数组中搜索满足指定谓词条件的第一个元素。

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用于搜索元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 用于定义匹配数组元素的条件的谓词 |

### 返回值

数组中满足谓词定义的条件的第一个元素的副本；如果不存在，则返回类型 T 的默认值

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [Predicate](../../predicate/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)