---
title: TrueForAll()
second_title: Aspose.Slides C++ API 参考
description: 确定指定数组中的所有元素是否满足由指定谓词定义的条件。
type: docs
weight: 677
url: /zh/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

确定指定数组中的所有元素是否满足由指定谓词定义的条件。

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 元素，用于匹配条件 |
| match | [System::Predicate](../../predicate/)\<T\> | 用于定义匹配数组元素条件的谓词 |

### 返回值

如果数组 arr 的所有元素满足由谓词 match 定义的条件，则为 true；否则为 false

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)