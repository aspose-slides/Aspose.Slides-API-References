---
title: rbegin()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个指向翻转后容器的第一个元素的逆向迭代器。它对应于未翻转容器的最后一个元素。如果容器为空，返回的迭代器等于 rend().
type: docs
weight: 469
url: /zh/system/array/rbegin/
---
## Array::rbegin() 方法

返回一个指向翻转后容器的第一个元素的逆向迭代器。它对应于未翻转容器的最后一个元素。如果容器为空，返回的迭代器等于 [rend()](../rend/)。

```cpp
reverse_iterator System::Array<T>::rbegin() noexcept
```

### 返回值

指向容器最后一个元素的迭代器。

## Array::rbegin() const 方法

返回一个指向翻转后容器的第一个元素的逆向迭代器。它对应于未翻转容器的最后一个元素。如果容器为空，返回的迭代器等于 [rend()](../rend/)。

```cpp
const_reverse_iterator System::Array<T>::rbegin() const noexcept
```

### 返回值

指向 const 限定容器最后一个元素的迭代器。

## 另见

* 类型别名 [reverse_iterator](../reverse_iterator/)
* 类型别名 [const_reverse_iterator](../const_reverse_iterator/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)