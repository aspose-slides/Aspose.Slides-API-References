---
title: FindIndex()
second_title: Aspose.Slides C++ API 参考
description: 在指定数组中搜索满足特定谓词条件的第一个元素。
type: docs
weight: 638
url: /zh/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

搜索指定数组中满足特定谓词条件的第一个元素。

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用于在其中搜索元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 用于定义匹配数组元素条件的谓词 |

### 返回值

数组中满足谓词定义的条件的第一个元素的索引；如果不存在，则返回 -1

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [Predicate](../../predicate/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)