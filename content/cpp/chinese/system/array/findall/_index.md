---
title: FindAll()
second_title: Aspose.Slides C++ API 参考
description: 检索所有符合指定谓词定义的条件的元素。
type: docs
weight: 664
url: /zh/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

检索所有符合指定谓词定义的条件的元素。

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用于在其中搜索元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 一个定义用于匹配数组元素条件的谓词 |

### 返回值

一个 [Array](../)，其中包含所有符合指定谓词定义的条件的元素（如果找到）；否则，为空的 [Array](../)。

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [Predicate](../../predicate/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)