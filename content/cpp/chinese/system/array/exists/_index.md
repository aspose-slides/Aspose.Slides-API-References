---
title: Exists()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定的 Array 对象是否包含满足指定谓词要求的元素。
type: docs
weight: 781
url: /zh/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) 方法


确定指定的 [Array](../) 对象是否包含满足指定谓词要求的元素。

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 要在其中查找元素的数组 |
| match | std::function\<**bool**(T)> | 定义要求并检查元素是否满足这些要求的函数对象 |

### 返回值

True if **arr** contains an element that satisfies requirements defined by **match**（如果 **arr** 包含满足 **match** 定义的要求的元素，则返回 True）

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)