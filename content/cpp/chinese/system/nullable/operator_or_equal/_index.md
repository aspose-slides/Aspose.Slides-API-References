---
title: operator|=()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的值作为右侧参数，将 operator|=() 应用于当前对象所表示的值。
type: docs
weight: 261
url: /zh/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) 方法

使用指定的值作为右侧参数，将 [operator|=()](./) 应用于当前对象所表示的值。

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于使 SFINAE 工作的模板参数。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | **bool** | 布尔值，用作对当前对象所表示的值应用的 [operator|=()](./) 的右侧值。 |

## 返回值

对自身的引用。

## 另请参见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)